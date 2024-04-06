# PyChain with Transaction Records

![application-image](https://github.com/vchoppa0312/Module_18_Challenge/assets/144874369/a867e982-e3e4-4092-bb7a-b2ca78f0147d)

Using Dataclasses, a new **Record** data type with Sender, Receiver and Amount as parameters is created. The input data type is replaced with the Record data type in the **Pychain Ledger**, 
which, using Streamlit library, creates, adds, validates and displays new blocks with the transaction records on the PyChian Ledger.

## PyChain: Adding Blocks

A typical pychain Block Class includes the data pertaining to 'Record', 'Creator_ID', 'Prev_hash' i.e. hash of the previous block in the PyChain and 'timestamp'. **The Genesis Block** is
created at the inititaion of PyChain. For adding subsequent blocks, a mining process which adds a nonce to the data to produce a hash with specified number of leading zeros i.e. **difficulty**
is introduced.

## PyChain: Validating Blockchain

To validate the chain, the hash stored in the block is verified against the hash of previous block. This ensures that the chain is not tampered.

## PyChain: StreamLit Display

The PyChain class thus created with functions to create, add and validate blocks is displayed using StreamLit interface. Here, button function is used for user interation to add blocks,
write function to display outputs, text_input for user inputs etc,. Similarly, sidebar for visual appeal with slidebar for difficulty selection and block information display.

Here is the output:

[streamlit-pychain-2024-04-06-15-04-82.webm](https://github.com/vchoppa0312/Module_18_Challenge/assets/144874369/9c58f840-2608-45a3-afca-110732f7a76d)

