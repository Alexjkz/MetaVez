# MetaVez
## Introduction
 MetaVez is a web-based 3D avatar that can be prompted vocally and leverages advanced LLM technologies to provide insightful answers. 
 The avatar is currently designed to play the role of an intelligent assistant of the "BigRock" school. This can be easily changed via prompt engineering.


## Technology Used
 The project is built in Unity for WebGL and can run in any desktop browser. Mobile browser support is currently limited due to lack of compatibility on Unity.
 It leverages OpenAI Whisper speech-to-text, speech-to-text and ChatGPT APIs. For microphone integration in Unity we created a custom plugin (JSLIB module) that activates the browser's recording. Avatar is built using ReadyPlayerMe, and lipsync is managed trough uLipSync. 
 In the following image is shown a simplified structure of the project.
 
![VezAvatar documentation (1)](https://github.com/IChrono/Il-Vez-Avatar/assets/74292381/9333419b-2480-49f4-a52e-bb82f50e4d91)


## Getting Started
To use MetaVez is sufficient to visit the following link 

## Technology drill-down
The project uses different C# modules that dialogue with each other the "VezManager" is the main module. The following image provides detailed insight in the module structure.

![VezAvatar documentation](https://github.com/IChrono/Il-Vez-Avatar/assets/74292381/b84bdd88-3a30-48d7-8bfe-4b5930e3c438)
