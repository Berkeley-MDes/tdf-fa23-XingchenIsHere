# Report 11 - Week of 11/06/2023

## Progress
To integrate the chatbot into a separate personal website, API is crucial in this project. And for someone who has no prior experience with that, it has been quite a learning curve.

The challenges became more and more complicated as I delved deeper into connecting my webpage to the app. The first is, of course, comprehending what API and related concepts mean and how I should weave it into my code. Then after I built a simple webpage following ChatGPT’s instructions, the requests and responses were blocked by CORS policy, which required me to again understand what that meant and figure out new approaches to code. Finally, after I solved the previous problem, the console didn’t display any error messages when I ran my webpage, but I couldn’t receive any responses from my app. At this point the challenge has evolved into a debugging problem in the domain of web development, which is somewhat out of our project scope.
![](w-11-1.jpg)

To solve the obstacles, I consulted ChatGPT and my peers each time a new challenge emerged, and embedded what I learnt into my code.

I first figured out what the provided code related to API from Zerowidth meant. An API (Application Programming Interface) is a set of rules and definitions that allows one software application to interact with another. It acts as a bridge that enables two applications to communicate with each other. An API key is a unique identifier used to authenticate a user, developer, or calling program to an API. It is a secret token that is often used to control access and track API usage. An API response packet is the data sent back by the server in response to an API request. It usually contains a status code indicating whether the request was successful, along with the requested data or an error message in the body of the response. And a POST request body is the part of an HTTP POST request where data sent by the client to the server is contained. It's used when you need to send data to the API server to create or update resources.

Then the CORS policy drove me to use server-side code to relay requests by creating a backend server to handle frontend requests and sending them to the API of the Zerowidth app.

Furthermore, confronted with the bug without error messages, I figured out that I didn't handle the format of the request header and body after careful observation.

After fixing that, I could finally get the chatbot’s response to my first prompt, but all my following prompts were unattended. I think this may be related to the lack of manually maintaining the status and sessions of the conversations. Due to the limited time, I decided to put this problem aside and focused on finishing a demonstrative prototype, and come back to it in the future.


## Reflections
Two aspects that can be improved were mentioned in my peers' feedback. One is the expectation that I can go beyond designing a mini-me to answer TDF-related questions and build tools that can store other data and be used in more various ways. The other is advice on my presentation video. Although some found it interesting to have my “mini-me” speak for me in the video, some found it hard to follow with the automated voice and without matching visuals and footage.

Moving forward, I plan to expand the chatbot's functionalities to encompass a broader range of data storage solutions and build a more personalized tool that’s actually useful to me, like a personal library or a tool that helps me write lyrics. so that it can work in a variety of contexts beyond TDF-related inquiries. I would love to further explore that. Additionally, to enhance clarity and engagement, I will experiment with different text-to-speech technologies to find a more natural-sounding voice for my "mini-me". I also aim to incorporate more dynamic visuals and relevant footage that better align with the spoken content in my future presentation videos, ensuring that the visuals complement the narrative and facilitate a more immersive and understandable viewing experience.


## Speculations
LLMs’ capability of quickly retrieving wanted information from a sea of data and presenting it in an accessible way can open doors to new possibilities in engineering. For example, LLMs can provide engineers with access to vast amounts of technical documentation and research, helping to inspire new design approaches. LLMs can also assist engineers in risk assessment by providing insights from a large corpus of case studies and historical data, leading to better-informed decisions. Moreover, engineers can use LLMs to understand complex documentation or to translate and summarize technical material, making it more accessible. Overall, AI and LLMs can optimize existing processes and foster innovation, efficiency, and safety.
