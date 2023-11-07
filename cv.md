# Nurmukhammed Omirzak

## How to Reach Me

- **Telegram**: [@nrmkhd](https://t.me/nrmkhd)
- **LinkedIn**: [/in/nurmukhammed](https://www.linkedin.com/in/nurmukhammed/)
- **GitHub**: [@nuromirzak](https://github.com/nuromirzak)

## About Me

I am a senior computer science student specializing in web development. Initially, I developed backend applications using Spring Boot, but over time, I decided to explore frontend development. I find frontend development to be more dynamic and visually engaging, allowing me to see the results of my work instantly. Additionally, I love that the community surrounding frontend development is highly active and welcoming.

## Skills

- Java (Spring Boot)
- Express.js
- HTML/CSS

## Sample Code Showcase

Here I provide solution for problem to find whether the given strings are anagrams or not.

```java
class Solution {
    public boolean isAnagram(String s, String t) {
        if (s.length() != t.length()) {
            return false;
        }

        int[] map1 = new int[26];
        int[] map2 = new int[26];

        for (int i = 0; i < s.length(); i++) {
            map1[s.charAt(i) - 'a']++;
            map2[t.charAt(i) - 'a']++;
        }

        for (int i = 0; i < 26; i++) {
            if (map1[i] != map2[i]) {
                return false;
            }
        }

        return true;
    }
}
```

## Work Experience

I don't have any work experience yet, but you can see my projects on my GitHub profile.

1. Clone of genius.com for kazakhstani songs: [Aqyndar](https://github.com/nuromirzak/aqyndar)
2. Clone of pastebin.com: [Sharing codes](https://github.com/nuromirzak/sharing-codes)

## Education

- Astana IT University
    - Bachelor of Computer Science
    - 2021 - 2024 (Expected)
    - GPA: 3.3

## Languages

1. English: Intermediate [^1]
2. Kazakh: Native
3. Russian: Intermediate

[^1]: I have a certificate of IELTS with overall score of 6.5, but I haven't practiced English for a long time, so I'm not sure about my current level.
