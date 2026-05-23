# 🏋️ AI-Powered Gym Assistant Chatbot

An intelligent conversational AI assistant for gym members that provides personalized fitness insights and answers using Google Generative AI and real gym member data.

## 📋 Features

- **Interactive Q&A Interface**: Ask questions about gym performance, workouts, and fitness metrics
- **Data-Driven Insights**: Analyzes 1000+ gym member records for accurate recommendations
- **Real-time Analytics**: Tracks average calories burned, session duration, and workout patterns
- **AI-Powered Responses**: Uses Google Generative AI for intelligent, contextual answers
- **Easy Integration**: Built for Google Colab with minimal setup required

## 📊 Dataset

**gym_members_exercise_tracking.csv**

Contains 1000+ records with the following metrics:
- **Demographics**: Age, Gender, Height, Weight, BMI
- **Heart Rate Data**: Max BPM, Average BPM, Resting BPM
- **Workout Info**: Session Duration, Calories Burned, Workout Type
- **Health Metrics**: Fat Percentage, Water Intake, Experience Level
- **Activity**: Workout Frequency (days/week)

### Workout Types Tracked:
- Yoga
- HIIT (High-Intensity Interval Training)
- Cardio
- Strength Training

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)

1. Open the notebook in Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepan11223344-ui/AI-GYM-Chatbot/blob/main/AI_Gym_Chatbot.ipynb)

2. Run all cells to load dependencies and data
3. Start chatting with the gym assistant!

### Option 2: Local Setup

```bash
# Clone the repository
git clone https://github.com/deepan11223344-ui/AI-GYM-Chatbot.git
cd AI-GYM-Chatbot

# Install dependencies
pip install pandas google-generativeai

# Run the chatbot (requires setup of local environment)
python gym_chatbot.py
```

## 💬 Example Questions

```
"What is the average calories burned per session?"
"Which workout type burns the most calories?"
"What is the average BMI of our members?"
"How long is a typical gym session?"
"What's the correlation between session duration and calories burned?"
```

## 🔧 Technical Stack

- **Python 3.8+**
- **Pandas**: Data analysis and processing
- **Google Generative AI**: AI-powered responses
- **Google Colab**: Cloud-based notebook environment
- **GitHub**: Version control and repository hosting

## 📁 Repository Structure

```
AI-GYM-Chatbot/
├── AI_Gym_Chatbot.ipynb              # Main Google Colab notebook
├── gym_members_exercise_tracking.csv  # Dataset with 1000+ member records
├── README.md                          # This file
└── requirements.txt                   # Python dependencies
```

## 🎯 Use Cases

1. **Member Support**: Answer common fitness questions
2. **Data Analytics**: Get insights into member workout patterns
3. **Personalized Recommendations**: Provide data-driven fitness advice
4. **Performance Tracking**: Monitor average metrics across the gym
5. **Health Insights**: Analyze correlations between different health metrics

## 📊 Data Statistics

Based on the gym member dataset:
- **Total Members**: 1000+
- **Average Calories Burned**: ~905 per session
- **Average Session Duration**: ~1.26 hours
- **BMI Range**: 13-48
- **Age Range**: 18-59 years
- **Experience Levels**: 1-3 (Beginner to Advanced)

## 🔐 API Key Setup

To run this locally with Google Generative AI:

```python
import google.generativeai as genai

# Set your API key
genai.configure(api_key="YOUR_API_KEY")

# Create model instance
model = genai.GenerativeModel('gemini-pro')
```

Get your free API key: https://makersuite.google.com/app/apikey

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add more data to the dataset
- Enhance the AI prompts
- Create additional analysis notebooks
- Suggest new features

## 📝 License

This project is open source and available under the MIT License.

## 📞 Support

For issues or questions:
1. Check the GitHub Issues tab
2. Review existing documentation
3. Create a new issue with detailed description

## 🌟 Features Coming Soon

- [ ] Multi-language support
- [ ] Personalized member profiles
- [ ] Workout recommendations based on goals
- [ ] Progress tracking over time
- [ ] Integration with fitness APIs
- [ ] Mobile app interface

## 👨‍💻 Author

**Deepan A**
- GitHub: [@deepan11223344-ui](https://github.com/deepan11223344-ui)
- Repository: [AI-GYM-Chatbot](https://github.com/deepan11223344-ui/AI-GYM-Chatbot)

---

**Last Updated**: May 23, 2026  
**Status**: ✅ Active Development
