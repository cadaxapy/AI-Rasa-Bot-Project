﻿## Setup and installation

If you haven’t installed Rasa NLU and Rasa Core yet, you can do it by navigating to the project directory and running:  
```
pip install -r requirements.txt
```

You also need to install a spaCy English language model. You can install it by running:

```
python -m spacy download en
```

## How to use this?
- NOTE: If running on Windows, you will either have to [install make](http://gnuwin32.sourceforge.net/packages/make.htm) or copy the following commands from the [Makefile](https://github.com/RasaHQ/starter-pack-rasa-stack/blob/master/Makefile)
1. You can train the Rasa NLU model by running:  
```make train-nlu```  
This will train the Rasa NLU model and store it inside the `/models/current/nlu` folder of your project directory.

2. Train the Rasa Core model by running:  
```make train-core```  
This will train the Rasa Core model and store it inside the `/models/current/dialogue` folder of your project directory.

3. In a new terminal start the server for the custom action by running:  
```make action-server```  
This will start the server for emulating the custom action.

4. Test the assistant by running:  
```make cmdline```  
This will load the assistant in your terminal for you to chat.