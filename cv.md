# Denis Kuznetsov

## Contacts
- **Location:** Gomel, Belarus 
- **Phone:** +375 (25) 747-82-23
- **E-mail:** detrevile3@gmail.com
- **Discord:** Denis Kuznetsov (@dezmoss)
- **GitHub:** [Dezmoss](https://github.com/Dezmoss)
- [Facebook](https://www.facebook.com/profile.php?id=100010526264463)

## About Me
I am a beginner front-end developer, in my youth I was engaged in algorithmic programming competitions, I took part in regional competitions many times and was awarded a diploma. Currently I am actively studying web development courses. In the future, I want to become a full-stack developer.

## Skills
- HTML5
- CSS3
- SCSS/SASS
- JavaScript
- Git/GitHub
- Gulp
- BEM

## Code example
**Are they the "same"? KATA from Codewars:** *Given two arrays a and b write a function comp(a, b) (orcompSame(a, b)) that checks whether the two arrays have the "same" elements, with the same multiplicities (the multiplicity of a member is the number of times it appears). "Same" means, here, that the elements in b are the elements in a squared, regardless of the order.*

```
function comp(array1, array2) {
    let counter = 0;

    if (array1 && array2) {
        array1.forEach(num => {
            if (array2.indexOf(num ** 2) != -1) {
                array2.splice(array2.indexOf(num ** 2), 1);
                counter++;
            }
        });
        if (counter === array1.length)
            return true;
        else
            return false;
    } else
        return false;
}
```

## Education

- **Gomel State Technical University**, Energy Engineer
- **UDEMY**
    - *Web-developer* ([sertificate](https://www.udemy.com/certificate/UC-bf16dc3e-095b-4f54-983a-f8afcb63d722/))
    - *Full JavaScript and React.js course: from zero to result (in progress)*

## Languages
- English - Pre-intermediate A2
- Russian - Native