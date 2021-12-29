# APIMatchmak running steps

1. Use getSDKVersion.py to get the SDK Version (including the min SDK version and target SDK version) of each app.

2. Use PresolvedCSVFilter.py to solve the descriptions.

3. Use lib/APIExtractor.jar to extract the method declarations and method invocations of each app.

4. Use the DatasetGenerator.py to generate the datasets for evaluation.

5. Run main.py to start.