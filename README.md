# Check-endianness-of-the-computer-

Big endian and little endian are two formats to store multibyte data types into computer's memory. These two formats are also called network byte order and host byte order respectively. In a multibyte data type such as int or long or any other multibyte data type the right most byte is called least significant byte and the left most byte is called most significant byte. In big endian format the most significant byte is stored first, thus gets stored at the smallest address byte, while in little endian format the least significant byte is stored first.

Input Format

Input for this problem is 0x65543255

Constraints

Write program for the given input only and input is in Hexadecimal format.

Output Format

Underlying architecture is little endian

Sample Input 0

0x65543255

Sample Output 0

Underlying architecture is little endian.

Sample Input 1

65543255

Sample Output 1

INVALID INPUT

