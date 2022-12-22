# cyber-sercurity-unit-7
vulnerabilities of word press version 4.2

# Project 7 - WordPress Pen Testing

Time spent: **12** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pen Testing Report

### 1. (Required) Vulnerability Name or ID

- [x] Summary: 
  - Vulnerability types: this is a cross site request forgie I made though a from from my website ( https://vidacelinda.github.io ) which is hosted on my github. My website just make a comment to the word press 
  - Tested in version: 4.2
  - Fixed in version: 4.2.34
- [x] GIF Walkthrough:first It shows my github along with the form on my website. second, I go to my website which then automaticly directs me to word press and posts the comment I wrote in the form which was "2.cross site request forgie – I made a commnet done by using a form(website) hosted on my git hub"
  ![ezgif com-gif-maker-6](https://user-images.githubusercontent.com/87499194/200404554-852fd2bf-b57a-4d03-b239-213c43d2d564.gif)
- [x] Steps to recreate: First, I made a form on my github with a form because i will use github to host my website. second, I go to my website which then automaticly directs me to word press and posts the comment I wrote in the form which was "2.cross site request forgie – I made a commnet done by using a form(website) hosted on my git hub"
- [x] Affected source code: 
  - [Link 1](https://wordpress.org/news/2022/10/wordpress-6-0-3-security-release/)

### 2. (Required) Vulnerability Name or ID

- [x] Summary: 
  - Vulnerability types: Pupload Same Origin Method Execution (SOME
  - Tested in version:4.2
  - Fixed in version: 4.2.8
- [x] GIF Walkthrough: ![ezgif com-gif-maker-7](https://user-images.githubusercontent.com/87499194/200424551-5a4f288b-0fee-432c-8a20-10bf1bc71511.gif)

- [x] Steps to recreate: you can take advantage of the comment sections in word press and post a malitious link using javascript.What is show is me writing a java scrip on a comment sectioin which will make a button. once the button has been pressed then it will pop an alert however it can also be a link aswell but for this example i left it as a alert.
- [x] Affected source code:
  - [Link 1](https://wordpress.org/news/2016/05/wordpress-4-5-2/)

### 3. (Required) Vulnerability Name or ID

- [x] Summary: 
  - Vulnerability types:Pupload Same Origin Method Execution (SOME
  - Tested in version:4.2
  - Fixed in version:4.2.8
- [x] GIF Walkthrough: ![ezgif com-gif-maker-8](https://user-images.githubusercontent.com/87499194/200427815-9d19a29c-e522-4465-89d7-3abe026c30d5.gif)
- [x] Steps to recreate: I made a post using CSS that has an alert that pops up on the top of the titile page.Note this does not okly have to be an alert but it could also be a link.
- [x] Affected source code:
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with  ...
<!-- Recommended GIF Tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2022] [name of copyright owner :Carlo Leiva]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
