# A Simple Framework for Federated Learning

A simple federated learning framework based on FedSimSiam that allows for sequential training of clients. 
To apply it to you use-case, change the following:
- Change the model in *server.py*
- Use your own *create_datasets* method in *server.py*
- Change the *client_update* method in *client.py* to train your local models accordingly