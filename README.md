A simplified simulation of the Enigma Machine, the famous WWII-era electro-mechanical rotor cipher machine, written in Go (Golang). This project models the core functionality of the Enigma, including:

Rotor encryption logic

Reflector behavior

Plugboard substitution

Rotor stepping mechanism

Bidirectional encryption/decryption (Enigma's symmetry)


Features
Implements 3 rotors (I, II, III) with customizable wirings and positions

Supports a plugboard (steckerverbindung) for initial/final substitution

Includes reflector B

Preserves Enigma's symmetric encryption, allowing decryption using the same procedure

Ignores non-alphabetic characters (keeps them as-is)

Written in clean, readable Go
