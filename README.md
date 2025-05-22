# medical-o1-sft

This repository contains a Jupyter Notebook implementing a **Medical Tool** that integrates multiple Google APIs for location-based medical assistance. The tool also interacts with a fine-tuned medical model (`medical-o1-sft`).  

## Features 

- **Google Geolocation API** : Determines the user's approximate location.  
- **Google Places API** : Finds nearby medical facilities.  
- **Google Distance Matrix API** : Calculates travel distance and time to medical locations.  
- **Integrated Location & Places Function** : Combines all three APIs for seamless data retrieval.  
- **Medical Model Call Function** : Communicates with `medical-o1-sft` to provide relevant medical insights.  

## Installation   

Clone the repository and install the required dependencies:  

```
git clone https://github.com/yourusername/medical-tool.git
cd medical-tool
```

## Libraries required

```
pip install google
pip install pyaudio
pip install queue
pip install re
pip install sys
pip install time
pip install threading
pip install gradio
pip install google.generativeai
pip install openai
pip install dotenv
```
## Usage 

Run the Jupyter Notebook:  

```
jupyter notebook medical-tool.ipynb
```

## API Keys   

Ensure you have valid **Google API keys** for Geolocation, Places, and Distance Matrix services. You can ask the owner of this Github repo for the API keys.   

## License 

This project is licensed under the MIT License.  


## Contributors

[Yash Mishra](https://github.com/yash-mishraa)


