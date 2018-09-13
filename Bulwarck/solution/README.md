# Solution

1.) Review the Source Code

2.) Create a `constructor` to execute exploit code to bypass `blooper` function

3.) Use another smart contract to exploit the challenge contract to bypass origin validation

4.) Use the last 8 bits to bypass other check.

5.) keccak("aaa","ppp") == keccak("aaap","pp") will always return TRUE. That trick is utilized here. 

6.) Run the Exploit code & You will become owner
