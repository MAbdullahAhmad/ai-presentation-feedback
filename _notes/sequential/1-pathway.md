# Presentation Analyzer

### Steps

1. Recorded Video
2. Audio ~> STT (`faster-whiser`) Text (`no-GPU`)
3. Body-Language & Facial-Expression: `MediaPipe` Live-Feed ~> Controller ~> JSON (`no-GPU`)
4. LLM


### LLM Usage

```
[system] "i shall give you json data with abc. report"
[admin]: "example"
[user] {presentation-data}
[assistant] {report}
```

- Prompt Engineering (branch AI)
- App Development (Web-Based)
- 90%+ 97-98%

### ML Algo

- Cosign similarity (word distances)
- 70%

Collect data:

- 20-50 presetnation (at least)
- results.

- Machine Learning (Core AI) - Math Algo
- App Development

AI  / CS ?

BSAI
MSAI

```
[00:00]  
Hello! My name is Muhammad Hamza!

[00:10]  
I am an AI Developer and Full Stack Web Developer with over 5 years of experience.

[00:20]  
I specialize in AI and chatbot integration, creating high-performance web applications, and delivering business solutions.

[00:30]  
To date, I’ve successfully completed 30+ global projects and 10 local projects, maintaining a 100% job success rate.

[00:40]  
I focus on Laravel, PHP, server management, and automation to build complex multi-user systems.

[00:50]  
Thank you for your time! I look forward to connecting with you!
```

70%
professionalism = 0.8
clearity = 0.9
issues = 0.2

```
[00:00]  
Hello! My name is Muhammad Hamza!

[00:10]  
I am an AI Developer and Full Stack Web Developer with over 5 years of experience.

[00:20]  
I specialize in AI and chatbot integration, creating high-performance web applications, and delivering business solutions.

[00:30]  
To date, I’ve successfully completed 30+ global projects and 10 local projects, maintaining a 100% job success rate.

[00:40]  
I focus on Laravel, PHP, server management, and automation to build complex multi-user systems.

[00:50]  
Thank you for your time! I look forward to connecting with you!
```

70%
professionalism = 0.8
clearity = 0.9
issues = 0.2

```
[00:00]  
Hello! My name is Muhammad Hamza!

[00:10]  
I am an AI Developer and Full Stack Web Developer with over 5 years of experience.

[00:20]  
I specialize in AI and chatbot integration, creating high-performance web applications, and delivering business solutions.

[00:30]  
To date, I’ve successfully completed 30+ global projects and 10 local projects, maintaining a 100% job success rate.

[00:40]  
I focus on Laravel, PHP, server management, and automation to build complex multi-user systems.

[00:50]  
Thank you for your time! I look forward to connecting with you!
```

70%
professionalism = 0.8
clearity = 0.9
issues = 0.2

```
[00:00]  
Hello! My name is Muhammad Hamza!

[00:10]  
I am an AI Developer and Full Stack Web Developer with over 5 years of experience.

[00:20]  
I specialize in AI and chatbot integration, creating high-performance web applications, and delivering business solutions.

[00:30]  
To date, I’ve successfully completed 30+ global projects and 10 local projects, maintaining a 100% job success rate.

[00:40]  
I focus on Laravel, PHP, server management, and automation to build complex multi-user systems.

[00:50]  
Thank you for your time! I look forward to connecting with you!
```

70%
professionalism = 0.8
clearity = 0.9
issues = 0.2


### FYP I
- Jury (Accept / Reject)
- Incharge + Supervice

### FYP II
- Jury (Accept / Reject)
- Incharge + Supervice



Supervisor = No Issue (ML / GPT)
Project Teacher (ML Teacher) = Project Incharge = ?

FYP Idea
- Idea Defence = 3-5 Approve / Reject
- Student ~> Supervisor + Co-Supervisor
- Defence I (7th end) - 3-5 Jury (Doc)
- Defence II (8th end) - 3-5 Jury (Doc + Dev)


### 
- Dataset Generation
- Training

Model ?
Cosign Similary
Machine Learning


### Cosign Similarity

1. Dataset Collection:
    - Videos
    - MediaPipe ~> CSV expressions
    - STT ~> transcript
2. Preprocessing:
    - cleaning
    - fillna, outliars
    - words ~> numeric (OneHotEncing)
3. Train (Model) ?
4. Test

Binary
LR ... R
plot:
- size
- location
- city
- floors
- price ?


hello = 1
my = 2
name = 3
abdullah = 4
thank = 5
you = 6

good:

w : f
5 : 10
6 : 10
5~>7 : 5
1 : 3
2: 0

bad:

w : f
5 : 10
6 : 10
5~>7 : 5
1 : 3
2: 0

test:

0.78 probab good
78%

0.21 probab bad 
21 %


Result:
Good

good = 0.71
professional = 0.81
vague = 0.21


good = 71%
professional = 81%
vague = 21%


word = dimension


x, y (2d)
x, y, z (3d)


hello = 1
my = 2
name = 3
abdullah = 4
thank = 5
you = 6
name = 3
abdullah = 4
thank = 5
you = 6
name = 3
abdullah = 4
thank = 5
you = 6



LLaMa 3B, 7B, 13B

3Billion Params
3 Billion dimensions

point


- SVM
- KNN

- Cosign
- Distance (3-4)


Deep Level AI
CS 2-3

basic output
LLM


PResentation Videos

7d

Videos:
- good presentation
- bad presentation

- text
- body language
- facial expression
- timestamps


100 presentations:
- 50 good
- next 50 bad

```
dataset/
. good/
. . v1.json
. . v2.json
. . v3.json
. . v4.json
. bad/
. . v1.json
. . v2.json
. . v3.json
. . v4.json
```

```json
{
    "name": "ABC",
    "text": "Lorem ipsum dolor sit amet consectetur, adipisicing elit. Velit sequi deleniti in fugiat qui, beatae repellendus obcaecati incidunt iure dolore quisquam dolores nihil eaque ea ut voluptates similique molestias quibusdam?",
    "facial-expression": [
        {
            "name": "angry",
            "raw": {
                "lip": {
                    "x1": 1,
                    "x2": 1,
                    "y1": 1,
                    "y2": 1
                }
            },
            "timestamp": "2024-02-03 03:35:33:412"
        }
    ],
    "body-language": [
        
    ],
}
```

