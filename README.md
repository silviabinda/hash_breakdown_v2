# Hash Breakdown v2, 2024

NOTE: Hash Breakdown v2 is a reduced version of the artwork Hash Breakdown (https://github.com/silviabinda/hash_breakdown), and was made specifically for the Dutch Design Week 2024 exhibition curated by Baltan Laboratories. 
DIFFERENCES to original version: The version v2 differs in the number of 3D printed modules used, the color palette chosen, the overall dimension of the artwork and the number of electronic modules used. These changes implicate minor changes to the codes as well. Overall, the functionality and concept of the artwork do not change. 

## About
Hash Breakdown v2 is a critical interface constituted by an electronic and digital ensemble of microcomputers, modules, 3D prints, sensors and codes with real-time functionality. The system parses sentences related to the keywords “feminism is” from the World Wide Web and then initiates a slowed-down explanatory process of converting the parsed sentence into a hash using the SHA-256 (Secure Hash Algorithm 256-bit) algorithm.
 
A hash is a mathematical function that converts an input of arbitrary length into an encrypted output of a fixed length. The SHA-256 hash was chosen for this project because it is broadly used in various digital operations such as data integrity verification, password storage, and digital signatures, and it forms an integral component of the Bitcoin blockchain, enabling the proof-of-work (PoW) consensus algorithm.
 
The artwork articulates critique directed towards the mystifying, elitist and masculine narrative around algorithms and the blockchain. The purpose of Hash Breakdown v2  is to demystify, decompose, slow down and break down the hashing process of a SHA-256 algorithm. What normally takes less than a millisecond is here extended into a 4-minute explanatory cycle, represented visually within a structure imitating parts of a simplified logic gate diagram of the very same SHA-256 hashing function. 
 
Through a router connected to a Raspberry Pi, the ESP32 microcontrollers receive partial data needed for different stages of the hashing process. The data to be hashed is generated automatically by a script that returns the first results of the search for the words “feminism is” in the DuckDuckGo search engine. For this, a Python implementation of the SHA-256 hashing algorithm was used and modified in such a way that each step is represented visually or sonically, making the hashing algorithm transparent and comprehensible for visitors.
