# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

Reasoning - <br>
After installing WSL and gcc on the distro, I compiled `zeroth.c` and obvious error was in the line `int ved[] = " ... ";`. Changed to `char` array, which on running gave the following output

```
What manual page do you want?
For example, try 'man man'.
```

---

## Your first approach below (first.txt)

Reasoning - <br>
There's a subtle hint in the file `zeroth.c` for this challenge, `#define clue_of_1 "not rot13 try all"` suggesting a Caesar cipher (ROT##). After `cat`ting `first.txt` and feeding into some online Caesar cipher decrypter, I get the following (ROT18)


```
noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT
```

---

## Your second approach below (strings.txt)

Reasoning - <br>
Installed `unzip` first, found the `strings.txt` file in `Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3/` folder. Found the last string `8dc2evcCSSc4kUy` written as (password), searched it's occurrence using `grep`, now tried the file names `strings.txt`, `eleven.txt`. It worked (unzipping `fourth.zip`).

```
1/5/0/3/strings.txt:8dc2evcCSSc4kUy (password)
eleven.txt:8dc2evcCSSc4kUy
final.txt:8dc2evcCSSc4kUy
```

---

## Your third approach below (fourth.zip)

Reasoning - Found the string `DevOps{...}` in `get_in/4/2_inner/0.txt` using `grep` command.

```
DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}
```

---


- Name : Nevish Pathe
- Roll : 220757
- GitHub username: npxx
- Discord username: DrNex#8672


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
