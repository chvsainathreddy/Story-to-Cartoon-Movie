# 🎬 Story to Cartoon Movie
Turn any short story into a narrated cartoon movie using AI and Python.

This project combines OpenAI (ChatGPT + DALL·E) for scene generation, gTTS for voice-over narration, and MoviePy for video creation — transforming simple text into a playable MP4 animated movie.

## ✨ Features
🖌️ AI-generated cartoon scenes using DALL·E

🎙️ Automatic voice-over narration with gTTS

🎞️ Video creation & stitching using MoviePy

⚡ Scene-by-scene synchronization of narration and images

🎥 Final output: MP4 video ready to share


## 📂 Project Structure

Story-to-Cartoon-Movie/
│
├─ notebook.ipynb          # Main Jupyter notebook (full pipeline)
├─ requirements.txt        # Project dependencies
├─ README.md               # Project description (this file)
├─ .gitignore              # Ignores output, voices, and large files
│
├─ images/                 # AI-generated images per scene
├─ voices/                 # gTTS-generated voice files
└─ output/                 # (Ignored) Final MP4 videos
⚠️ By default, images/, voices/, and output/ are ignored via .gitignore to keep the repository lightweight.

## 🛠 Installation
1️⃣ Clone the repository:


git clone https://github.com/YourUsername/Story-to-Cartoon-Movie.git
cd Story-to-Cartoon-Movie
2️⃣ Install dependencies:

pip install -r requirements.txt
3️⃣ Set up OpenAI API Key (for DALL·E image generation):

export OPENAI_API_KEY="your_api_key_here"
(or set in the notebook cell)

🚀 Usage
Open notebook.ipynb in Jupyter Notebook or VS Code.

Enter your story text (1 line = 1 scene).

Run all cells to:

Generate DALL·E cartoon images

Generate scene-wise voice-over with gTTS

Stitch everything into a narrated MP4 video

Check the output/ folder for your final video.

## 🎯 Example Workflow
Input Story (4 lines):


A tiny dragon lived in a bright, cozy cave.
He always dreamed of flying above the tall mountains.
One sunny day, he met a friendly bird who taught him to soar.
Together, they danced in the forest, feeling free and happy.
Output:  [Video](https://drive.google.com/file/d/1zhrJVQAnDtAoMallj7kdRTqufZ5wrVfp/view?usp=drive_link
) 
## ⚡ Next Improvements
 Optional background music (BGM)

 Smooth scene transitions (fade in/out)

 Export videos in 16:9 for YouTube

## 📜 License
This project is for educational and personal use.
Generated videos can be shared, but verify music/image licenses if publishing commercially.
