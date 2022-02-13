# Blockchain-based-ledger-system
This repository has for purpose to mimic the working of a blockchain. The purpose of this code is aimed to demonstrate how the hash is used in every block. Every block depends on the previous block and its hash. The result of the codes can be used on streamit : https://share.streamlit.io/tforg7/blockchain-based-ledger-system/main/pychain.py

This code used a python script that creates a record that contains: a sender, a receiver and an amount. This record is saved in a block that contains the last record as well as the hash of the previous record. This previous record is structured in the same way. As the hash is depending on the previous one, no hash or data can be altenated without affection the hash. This is a key element of the blockchain stucture.

The code is using a Streamlit application. This application allows to interact with a page where you can add new inputs. These inputs correspond with the data that is encoded in the record: a sender, a receiver and an amount. Every record is hashed and adds and additional hashed number, the nounce. This additional parameters helps to complexify the code. The nounce is usefull to add computional power when decrypting the code. 

Finaly to use the code in streamlit, you should do so, complete the following steps:

1. In the terminal, navigate to the project folder where you've coded the Challenge.
2. In the terminal, run the Streamlit application by using `streamlit run pychain.py`.
3. Enter values for the sender, receiver, and amount, and then click the "Add Block" button. Do this several times to store several blocks in the ledger.
4. Verify the block contents and hashes in the Streamlit drop-down menu.
5. Test the blockchain validation process by using the web interface.

![Streamlit app](screenshot Streamlit.jpeg)
