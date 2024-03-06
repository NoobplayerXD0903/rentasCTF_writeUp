# Question :
Assume that you are working for Law Enforcement, do you really got some IQ to investigate high profile criminals?

# Hint that was given :
**1.** The Sicarios…

**2.** You might think the given picture, is useless. Guessy. But its not. If u are about to investigate a crime group. You have to criminal-profile every single member of the group. E.g what they do, eat, visit, etc. If u recon, Blacky AKA Nelson Hernandez is the only sicarios that has went to uniten IG. U should focus on that acc only. For real - If u went to other sicarios, u will get lost. Next step? Technical stuff. Dig the flag inside the IG, metadata is there. That is how u profile someone, dig deeper as u could on that acc.

# The Flag :
***RWSC{Bl4cky_S1c4r1o}***

There was an image provided in the question (organization.jpg). **Below is the image attached**:
![organization](https://github.com/NoobplayerXD0903/rentasCTF_writeUp/assets/131782760/dbd2ef69-dc1e-47ff-8129-8cb83f32cd30)

# Solving method :
This was almost impossible to solve before the hint was given as there were no way to know that person we are looking for "Nelson Hernandez" is on Instragram and have visited the Uniten Official Instagram page. After the 2nd hint was given, the solving method become obvious.

**1st Step:**

Visit the uniten.official Instagram page with this link provided (https://www.instagram.com/uniten.official/)

**2nd Step:**

Go the united.offcial followers and from there Nelson Hernandez Instagram can be found

![image](https://github.com/NoobplayerXD0903/rentasCTF_writeUp/assets/131782760/75d22742-c891-4964-93ca-7e2199e57ab3)

Head into his Instagram profile and there is only one post that can be found in his IG.

![image](https://github.com/NoobplayerXD0903/rentasCTF_writeUp/assets/131782760/63881ca4-6df6-43b6-a711-01c3ace1ea20)

**3rd Step:**

From there, go into the post and right click on the post and "Save as".

![image](https://github.com/NoobplayerXD0903/rentasCTF_writeUp/assets/131782760/eb699c2c-49ae-494b-bea6-573b93ccc994)

A Chrome HTML Document of that specific will be downloaded like something as shown below: 

![image](https://github.com/NoobplayerXD0903/rentasCTF_writeUp/assets/131782760/4ccedb54-102f-4c13-a3bd-c5da9ced969f)

**4th Step:**

Open up the Chrome HTML Document and that Instagram page with JS will be shown as below:

![image](https://github.com/NoobplayerXD0903/rentasCTF_writeUp/assets/131782760/eba11dc0-b008-4291-9ac9-72a5143c81b5)

Right below, the flag can be located which happens to be the image file's name (Maybe)

![image](https://github.com/NoobplayerXD0903/rentasCTF_writeUp/assets/131782760/9b411b84-62b4-4f91-9484-125247ac25de)
