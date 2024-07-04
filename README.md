# hello-world

This is just a simple Python code to get started with your very first server.

To be able to run this code, you need to first make sure to install FastAPI ([https://fastapi.tiangolo.com/](https://fastapi.tiangolo.com/)) and Uvicorn ([https://www.uvicorn.org/](https://www.uvicorn.org/)).
This can be done by running pip install in a command window.

`pip install fastapi
pip install uvicorn`

After downloading the .py file, open a command window and navigate to the directory where the downloaded files are located.

Then run the following line:

`uvicorn main:app --port <port number of your choice>`.

Once done, your very first server should be up. Navigate to http://127.0.0.1/ on any web browser and you should see {"Hello": "World"}.

NOTE: This server is only available locally. To access this server remotely, you may host in on a cloud server or consider ngrok.



................
