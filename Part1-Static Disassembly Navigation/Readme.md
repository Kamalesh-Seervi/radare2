# Static Navigation Disassembly
# Basics Commands :

- To Run a binary file in radare2 type the below command to run it.

```
r2 ./letter_frequencies
```

- Now Seek commander will appear

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/124190e7-a5b8-4361-9869-7011147ac09c">

- Now type `V` you will get differents views of the binary file.
- Then if you type `p` after you pressed you can see different type of views like hex view, disassembly, debugger view, ascii hex, diffuse view and color visual etc.

### Hex View (ex)
 
<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/9bcbe86d-5233-4d9c-ad12-4a8cec3817e8">

- If you click enter the first line in disassembler is clicked (Like double clicking a line)

# Steps to analysis

- Type `Shift+:` to enter into seeker mode.
- Currently i am in disassembly mode under that i used `Shift+:`.

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/e64ad8f3-9994-4dc1-b61a-53775b4cd222">

- Now to analyse type `aaa` and enter .

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/4c5b6c26-95d0-4ec6-80cd-d68fe2182d7c">

- Then now type `afl` to display the functions in binary file.

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/5eec2d42-3b11-493f-ada0-246d64d92e23">

- From the above pic we want to see the main code in disassembly.
- So type `s main` and click enter **twice**.

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/e122ac2e-5e35-4367-a37d-037c62218854">

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/ec81650b-c721-43c5-a03a-9c60bc8fae3d">

- From the above pic now you can see that we have entered in to main code of disassembly.

- Basically in reverse engineering when go into a printf we get a stub code press `enter`.

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/20475b16-9eb4-4f5c-bc84-2d7c858b9215">

- Stub code of that printf

<img width="788" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/3d3799b6-fa0e-489b-9d61-c2024ad88b30">


### Note

- If you want to navigate back press `U`.


