# 2019LoggingBotTemplate
2019 Logging BotTemplate

Notes: <br />
Start from Samples <br />
EchoBot <br />
Right click > Manage Nuget packages > Click browse and look for Microsoft.Bot.Builder.Azure > Install <br />
Carry over TranslationMiddleware from MultilingualBot project <br />
Carry over AdapterWithErrorHandler <br />
Have a reference from Startup.cs to add AdapterWithErrorHandler (instead of the default adapter) </br >
Have a call to all the necessary middleware from AdapterWithErrorHandler <br />
