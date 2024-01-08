# Automatic recommendation of prognosis measures for mechanical components based on massive text mining
This repository contains the dataset used in:

*Jorge Martinez-Gil, Bernhard Freudenthaler, Thomas Natschläger: Automatic recommendation of prognosis measures for mechanical components based on massive text mining. Int. J. Web Inf. Syst. 14(4): 480-494 (2018)*

## 🌍 Overview
This dataset is a curated collection of multiple-choice questions focusing on the fundamentals of mechanical components. It is designed for checking the performance of analytical tools, providing insights into various aspects of mechanical technology, including mechanics, operations, and components.

If you use this work, please cite:

```
@article{martinez18,
  author       = {Jorge Martinez-Gil and
                  Bernhard Freudenthaler and
                  Thomas Natschl{\"{a}}ger},
  title        = {Automatic recommendation of prognosis measures for mechanical components
                  based on massive text mining},
  journal      = {Int. J. Web Inf. Syst.},
  volume       = {14},
  number       = {4},
  pages        = {480--494},
  year         = {2018},
  url          = {https://doi.org/10.1108/IJWIS-04-2018-0029},
  doi          = {10.1108/IJWIS-04-2018-0029}
}
```

### 📝 Dataset Structure
The dataset comprises ten questions, each with a set of four choices and a single correct answer. It is structured in JSON format, making it easily accessible and modifiable for various applications, such as quizzes, educational tools, and knowledge testing software.

### 📚 Contents
- `questions`: An array of question objects.
  - `question`: The question text.
  - `choices`: An array of possible answers.
  - `correct_answer`: The correct answer to the question.

## 🚀 Usage
This dataset can be utilized in various ways:
- **Quiz Applications**: Use as a base for quiz apps focusing on engineering, technology, or general science.
- **Data Analysis**: Analyze patterns in learning and understanding of steam engine technology.

## 📊 Example
```json
{
    "questions": [
        {
            "question": "What device is used to recycle the boiler water in steam engines?",
            "choices": ["Piston", "Water pump", "Cylinder", "Valve"],
            "correct_answer": "Water pump"
        },
        ...
    ]
}
```

## 📄 License
This dataset is available for free use and modification under the MIT License.