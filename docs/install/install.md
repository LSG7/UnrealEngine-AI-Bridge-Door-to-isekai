## We need to install three things.  

### 1. Download Mobile App  
'Door to isekai' operates solely on advertising revenue.   
So it requires ads to be displayed on the mobile app.  
The app only serves advertising and activation functions.  

### Dont download. It is now working. It will be ready soon
1. Please install the app.  
- Android : https://play.google.com/store/apps/details?id=com.doortoisekai.app
- ios : https://apps.apple.com/us/app/door-to-isekai/id6751532802

### 2. Downlaod Unreal Editor Plugin  
'Door to isekai' is implemented as an Unreal Engine plugin.  

1. Download the file that matches your required OS and UE version from the link.  
link : I will upload after ios releasing.  
2. Unzip to the following location: YourProjectRoot/Plugins/UnrealEngine_AI_Bridge (This is the standard installation method for Unreal Engine.)
3. You can find the our plugin in Plugins (Unreal Editor Menubar : Edit -> Plugins) [example image](https://github.com/LSG7/UnrealEngine_AI_Bridge/blob/main/docs/images/Plugins_0.png) 
4. You can open the our plugin panel at 'Unreal Editor Menubar Tools->Door to isekai' [example image](https://github.com/LSG7/UnrealEngine_AI_Bridge/blob/main/docs/images/Plugins_1.png)

### 3. Set up Ai Tools  [Youtube Manual](https://youtu.be/rIVxZb-hVF4)  

1. Set up AI tools     
Please check the installation method of each AI tool in the youtube video.  
After installing Python and Node, enter the following commands to install them.

         Gemini CLI  : npm install -g @google/gemini-cli  
         CLAUDE CODE : npm install -g @anthropic-ai/claude-code  
         Codex (GPT) : npm i -g @openai/codex
   
         after npm install, run python script
         (in your Unreal Project Root) : python3 ./Plugins/UnrealEngine_AI_Bridge/isekai_aitool_setting.py

         Claude Desktop : Youtube manual https://youtu.be/7LUHgiD3LDQ?si=z2gN2I6KSBrWbF_u

3. Notice  
'Door to isekai' is a bridge tool that connects external AI providers with Unreal Engine.  
**We do not provide the AI models directly.  Please sign up and subscribe to AI providers separately.**   
**Gemini CLI, Claude Desktop offers a free tier.**  Claude code, Codex CLI(GPT) is only available to paid users.  
This was a description of each AI provider's fee policy.  
The cost of using AI is determined by each provider (Google, OpenAI, Antropic).  
'Door to Isekai'  tool is operated solely on advertising.  
This means that with Gemini CLI free tier, you can use 'Door to isekai' just by watching ads.  
Alternatively, you can use a local LLM.



4. AI providers offering free tier  
   These are AI tools that can be used with 'Door to isekai'.  
   Gemini CLI, Claude Desktop  


### [Goto Next Step : How to use](https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai/blob/main/docs/howtouse/howtouse.md)
### [Goto Main](https://github.com/LSG7/UnrealEngine_AI_Bridge/tree/main)
