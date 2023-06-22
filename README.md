# Universe-Cipher
Universe Cipher

Lattice Creation: The program begins by creating a Cistercian lattice, which is a multi-dimensional data structure represented by nested vectors. The lattice is constructed based on the specified dimensions of width, height, depth, time, energy, spirit, mind, and soul. Each element of the lattice represents a LatticeSymbol, which contains a symbol identifier, color information, shade information, and complexity information.

Unicode Conversion: The program provides two utility functions to convert between Unicode and strings. The unicodeToString function takes a vector of Unicode code points and converts it into a string. The stringToUnicode function takes a string and converts it into a vector of Unicode code points.

Encryption: The program offers an encryptMessage function that takes a message and an encryption key as input. It uses a pseudorandom number generator to generate a random value for each character in the message. The random value is XORed with the Unicode code point of the character to encrypt it. The encrypted message is stored as a vector of Unicode code points.

Decryption: The program provides a decryptMessage function that takes the encrypted message and the encryption key as input. It performs the reverse operation of the encryption process by XORing each encrypted Unicode code point with the corresponding random value generated during encryption. The decrypted message is obtained as a string.

Main Function: The main function of the program showcases the usage of the aforementioned components. It creates a Cistercian lattice with specified dimensions, encrypts a sample message using an encryption key, and then decrypts the encrypted message using the same encryption key. The original message, encrypted message, and decrypted message are displayed on the console.

Overall, this program demonstrates a basic encryption and decryption mechanism using a Cistercian lattice as a data structure and Unicode code points for character representation.
