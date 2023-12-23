# Get Info of the Binary File

### rabin2
- To get the basic binary file info we use `rabin2`

```
rabin2 -I ./letter_frequencies
```
<img width="834" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/bd5e7186-bab8-40d6-b170-f38ceb970f32">

- If want in Hex try below command to get in hex value.

```
rabin2 -H ./letter_frequencies
```
<img width="834" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/b8365365-fa11-4f8e-bda4-195bf084c8bf">

- If you `zz` tag you will get atrings.

```
rabin2 -zz ./letter_frequencies
```

<img width="834" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/d16c1a5d-73de-4ce4-b4cf-58299f3f3279">


### rafind2

- We might think i can use grep for finding strings but its useful for normal files for binary files it best to use `rafind2`
```
rafind2 -s frequencies ./letter_frequencies
```
<img width="850" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/ef84aa7c-1145-4e91-88c8-b66b3e1d5979">


### To Load the headers

- We can use `r2 -nn ./letter_frequencies`
- You can also use `pf.` and `pf.elf_header @ elf_header`

<img width="962" alt="image" src="https://github.com/Kamalesh-Seervi/radare2/assets/107933310/f4914707-0333-468e-8fb1-39a5d39c9661">
