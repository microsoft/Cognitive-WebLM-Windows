# Microsoft Web Language Model API: Windows Client Library & Sample
This repo contains the Windows client library & sample for the Microsoft WebLM API, an offering within [Microsoft Cognitive Services](https://www.microsoft.com/cognitive-services), formerly known as Project Oxford.
* [Learn about the WebLM API](https://www.microsoft.com/cognitive-services/en-us/web-language-model-api)
* [Read the documentation](https://www.microsoft.com/cognitive-services/en-us/web-language-model-api/documentation)
* [Find more SDKs & Samples](https://www.microsoft.com/cognitive-services/en-us/SDK-Sample?api=weblm)


## The Client Library
The client library is a thin C\# client wrapper for the Microsoft WebLM API.


## The Sample
This sample is a C# Windows console application demonstrating the use of the Microsoft WebLM API.

To obtain a subscription key for WebLM API, visit [the Microsoft Cognitive Services website](https://azure.microsoft.com/free/cognitive-services/), create a new Azure account, and try Cognitive Services for free. Then open, modify, build, and run the accompanying Visual Studio solution.


### Build the sample
 1. Start Microsoft Visual Studio 2015 and select File \> Open \> Project/Solution.

 2. Starting in the folder where you clone the repository, go to the WebLM \> Windows Folder.

 3. Double-click the Visual Studio 2015 Solution file WebLMSample.sln.

 4. Paste your Microsoft Cognitive Services WebLM subscription key into the LMServiceClient constructor parameter value in Program.cs.

 5. Press Ctrl+Shift+B, or select Build \> Build Solution.

### Run the sample
After the build is complete, press F5 to run the sample.

A number of self-explanatory lines will be printed on the console, showing the results received from the WebLM service.

Press any key to exit the app.


## Contributing
We welcome contributions. Feel free to file issues and pull requests on the repo and we'll address them as we can. Learn more about how you can help on our [Contribution Rules & Guidelines](</CONTRIBUTING.md>). 

You can reach out to us anytime with questions and suggestions using our communities below:
 - **Support questions:** [StackOverflow](<https://stackoverflow.com/questions/tagged/microsoft-cognitive>)
 - **Feedback & feature requests:** [Cognitive Services UserVoice Forum](<https://cognitive.uservoice.com>)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


## License
All Microsoft Cognitive Services SDKs and samples are licensed with the MIT License. For more details, see
[LICENSE](</LICENSE.md>).

Sample images are licensed separately, please refer to [LICENSE-IMAGE](</LICENSE-IMAGE.md>).


## Developer Code of Conduct
Developers using Cognitive Services, including this client library & sample, are expected to follow the “Developer Code of Conduct for Microsoft Cognitive Services”, found at [http://go.microsoft.com/fwlink/?LinkId=698895](http://go.microsoft.com/fwlink/?LinkId=698895).
