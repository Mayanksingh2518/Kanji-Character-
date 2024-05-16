
```markdown
# Japanese Text Difficulty Analyzer

## Overview
This Python program analyzes the difficulty of Japanese text based on the strokes of Kanji characters present in the text.
 It uses the MeCab library for tokenization and NLTK for text analysis. The difficulty score is calculated based on the number of strokes of Kanji characters that fall within the top 5% strokes threshold.

## Requirements
- Python 3.x
- MeCab
- pandas
- seaborn
- matplotlib
- NLTK
- Kanji stroke dataset (e.g., Kanji_char.csv)

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/japanese-text-difficulty-analyzer.git
   ```
2. Install the required dependencies:
   ```
   pip install pandas seaborn matplotlib nltk mecab-python3
   ```
3. Download the Kanji stroke dataset (e.g., Kanji_char.csv) and place it in the same directory as the script.

## Usage
1. Prepare a text file (`testCases.txt`) containing the Japanese text you want to analyze.
2. Run the script `japanese_text_difficulty_analyzer.py`:
   ```
   python japanese_text_difficulty_analyzer.py
   ```
3. The program will read the Japanese text from `testCases.txt`, tokenize it using MeCab, analyze the Kanji characters' strokes, and calculate the difficulty score.

## Output
The program will output the difficulty score, which represents the number of difficult Kanji characters (i.e., characters with strokes in the top 5% threshold) in the text.

## Example
An example of Japanese text input:
```
新しい言葉や難解な漢字を学ぶことは言語学習の一部です。
```
Output:
```
Difficulty Score: 3
```

## Visualization
The program includes visualization functions to plot the strokes distribution and difficulty distribution in the Japanese text.

### Strokes Distribution Plot
This plot shows the distribution of strokes among Kanji characters present in the text.

### Difficulty Distribution Pie Chart
This pie chart illustrates the distribution of difficult and easy words in the Japanese text.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This README.md provides comprehensive instructions on how to use the code, install dependencies, and interpret the output. It also mentions the visualization functions included in the program and specifies the licensing information.
