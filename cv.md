# rsschool-cv

## Indira Moldakhmetova

### Contacts
* Location: Kazakhstan, Almaty
* Phone: +7-747-146-10-40
* Email: moldakhmetovai@mail.ru
* Telegram: https://t.me/heyitsindira
* GitHub: https://github.com/i-n-d-i

### About Me
I graduated from Moscow State University with a bachelor degree in computational mathematics and cybernetics. Now I'm working as a frontend developer at company named KaspiTravel. We are developing the top-1 application in Kazakhstan for buying air and train tickets. Currently I am working with JavaScript, Typescript and using the Angular framework. I love solving problems and learning new things. Now I want to learn the React and Vue frameworks and use them with confidence. I like to set myself challenges and I always try to fulfill them.
In terms of hobbies, I enjoy playing table tennis, board games, reading books and snowboarding.
I think that my main quality is that I learn something new very quickly, if I'm really interested in it.

### Skills
* HTML
* CSS
* JavaScript
* TypeScript
* Angular
* Git

### Code example
#### Longest Substring Without Repeating Characters from LEETCODE
*Given a string s, find the length of the longest substring without repeating characters.*
```
var lengthOfLongestSubstring = function(s) {
    if (s.length == 0) {
        return 0;
    }
    answer = 1;
    for (let i = 0; i < s.length; i++) {
        const hash = [s[i]];
        for (let j = i + 1; j < s.length; j++) {
            if (hash.includes(s[j])) {
                break;
            } else {
                hash.push(s[j]);
            }
        }
        answer = Math.max(answer, hash.length);
    }
    return answer;
};
```

### Education
* **Moscow State University - bachelor (2018-2022)**

### Experience
* **Backend web developer (intern) - QZhub, Nur-Sultan, June 2021 - August 2021**
  + Web development using Odoo ERP and CRM system
  + Writing own modules in Python
  + Support and correction of existing modules
************
* **Frontend web developer (angular) - Kaspi Travel, Almaty, June 2022 - present**
  + Setting up functionality and writing scripts
  + Creating interfaces from scratch
  + Verification and testing of the written functionality
  + Writing unit tests
 
### Languages
* English - Pre-intermediate/Intermediate
* Russian - native
* Kazakh - basic
