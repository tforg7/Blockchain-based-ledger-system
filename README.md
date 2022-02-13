# Blockchain-based-ledger-system
This repository has for purpose to mimic the working of a blockchain. The purpose of this code is aimed to demonstrate how the hash is used in every block. Every block depends on the previous block and its hash.

This code used a python script that creates a record that contains: a sender, a receiver and an amount. This record is saved in a block that contains the last record as well as the hash of the previous record. This previous record is structured in the same way. 

The code is using a Streamlit application. This application allows to interact with a page where you can add new inputs. These inputs correspond with the data that is encoded in the record: a sender, a receiver and an amount. Every record is hashed and adds and additional hashed number, the nounce. This additional parameters helps to complexify the code. The nounce is usefull to add computional power when decrypting the code. 


