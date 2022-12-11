#   `Bitwise Operation - Masking`

Bitwise operation is used for masking objects 

Lets create a basic images for understanding the Bitwise operation better.
<img width="698" alt="Screenshot 2022-12-11 at 7 01 43 PM" src="https://user-images.githubusercontent.com/91974776/206908459-a176a495-faaf-4933-81e9-4304c3917351.png">

By using the concept of Logic Gates functions 'or' 'and' 'xor' 'not' in the images, we can achieve masking.

`AND` -> intersection of two images

<img width="334" alt="Screenshot 2022-12-11 at 7 36 31 PM" src="https://user-images.githubusercontent.com/91974776/206908574-a990b1c5-3bf2-4073-b44b-bc9065768130.png">

`OR`  -> merges the two masks

<img width="316" alt="Screenshot 2022-12-11 at 7 36 37 PM" src="https://user-images.githubusercontent.com/91974776/206908597-26ec67dd-cfc7-4871-9be2-a011a2da73bb.png">

`XOR` -> removes the AND part from the OR mask

<img width="318" alt="Screenshot 2022-12-11 at 7 36 42 PM" src="https://user-images.githubusercontent.com/91974776/206908603-3e0334a2-983d-43aa-9b1e-6626cb056c63.png">

`NOT` -> takes only one image into consideration and inverses it 

<img width="314" alt="Screenshot 2022-12-11 at 7 36 47 PM" src="https://user-images.githubusercontent.com/91974776/206908623-228117bf-c095-45ea-96a4-466629eec435.png">
