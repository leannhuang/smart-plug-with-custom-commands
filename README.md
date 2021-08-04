# smart-plug-with-custom-commands
Voice control the smart appliance using the Percept DK hardware, TP-Link kasa sdk, and Custom Commands platform

The goal of this project is to be able to vocie control the smart appliance with the Percept DK device and Audio SoM using Azure Custom Commands as the platform.

## Prerequisites
- Percept DK ([Purchase](https://www.microsoft.com/en-us/store/build/azure-percept/8v2qxmzbz9vc))
- Azure Subscription : [Free trial account](https://azure.microsoft.com/en-us/free/)
- An Azure subscription key for Speech service: [Get one for free](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/cognitive-services/Speech-Service/overview.md#try-the-speech-service-for-free) or create it on the [Azure portal](https://portal.azure.com/)
- A Custom Commands app (see [Create a voice assistant using Custom Commands](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/cognitive-services/Speech-Service/quickstart-custom-commands-application.md) )
- Python 3.6+ (preferably an [Anaconda](https://docs.anaconda.com/anaconda/index.html) release)


## Device setup
1. Follow [Quickstart: unbox and assemble your Azure Percept DK components](https://docs.microsoft.com/en-us/azure/azure-percept/quickstart-percept-dk-unboxing) and the next steps.


### Python setup

1. If using Anaconda Python (recommended) [setup a conda environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html), otherwise, [use `venv`](https://docs.python.org/3/library/venv.html) to create a nuclear environment for this solution.
2. Install the Python dependencies as follows.

```
pip install -r requirements.txt
```

## Credits and references
- [TPLink Smart Home api](https://github.com/plasticrake/tplink-smarthome-api)
- [Azure Percept documentation](https://docs.microsoft.com/en-us/azure/azure-percept/)
- [Develop Custom Commands applications](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/how-to-develop-custom-commands-application)
