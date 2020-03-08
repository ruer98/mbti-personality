# mbti-personality
I explore trends between Myers-Briggs Personality Type Indicator (MBTI) personalities, use wordclouds to visualize common words for each personality type, and explore implications of text style transfer.

The MBTI is a personality type system that categorizes everyone into one of 16 personalities depending on 4 measurements:

- Inroversion (I) - Extroversion (E)
- Intuition (N) - Sensing (S)
- Thinking (T) - Feeling (F)
- Judging (J) - Perceiving (P)

The MBTI test is the most popular personality test in the world, and is based on Jungian Typology created by the psychologist Carl Jung. The test's validity has come into question due to the unreliable nature of experiments surrounding it, but nonetheless is still used all over the world for business, research, and personal use. While the test may not be too scientifically accurate, it is still useful in generalizing and understanding personlity types on a surface level.

### About the Data
The data was gathered through the PersonalityCafe forum, as it provides a large selection of people and their MBTI personality type, as well as what they have written. Keep in mind that the analysis I do is for fun and is only representative of the Personality Cafe forum and may not translate over into real-world application.

The dataset is 8675 rows with 2 columns:
- Type: The 4-letter MBTI code (INSTP, ENFJ, etc.)
- Posts: The last 50 things a user has posted, separated by "|||"

Data source: https://www.kaggle.com/datasnaek/mbti-type
