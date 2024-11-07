# Typing-Test
#### 1. Modules to Install

To run this code, you need Python’s built-in `random` and `time` modules. Both are included with Python, so no additional installation is required.

#### 2. What Does the Code Do?

This code implements a typing test game where users type a series of sentences, and their performance is evaluated based on accuracy and speed. Here’s a detailed breakdown:

1. Setup:
   - The code defines a list of sentences that will be used in the typing test. These sentences vary in difficulty and content.
   - An empty list is initialized to keep track of the best scores achieved during different runs of the test.

2. Running the Typing Test:
   - The `run_test` function is responsible for executing the typing test. It randomly selects a specified number of sentences from the list and shuffles them to ensure they appear in a different order each time.
   - A timer is started to measure how long it takes for the user to complete the test.
   - For each selected sentence, the user is prompted to type the sentence. The input is compared to the original sentence to check for correctness.
   - The user’s score is incremented for each correct sentence typed, and feedback is given indicating whether the typing was correct or incorrect.
   - After all sentences have been typed, the elapsed time is calculated. The number of words typed is used to compute the typing speed in words per minute (WPM).
   - The results are displayed, including the total score, elapsed time, and WPM.

3. Displaying Best Scores:
   - The `display_best_scores` function shows the list of best scores recorded from previous test runs. The scores are displayed in descending order. If there are no scores, it indicates that no scores have been recorded yet.

4. Execution:
   - The typing test is run with a predefined number of sentences (in this case, 5). After the test, the best scores are displayed.

#### How It Works

- Initialization:
  - The list of sentences is set up, and an empty list for best scores is initialized.
  
- Test Execution:
  - The code randomly selects and shuffles a set of sentences.
  - A timer starts, and the user types each sentence. The code checks for correctness and calculates the score and WPM based on the user’s performance.

- Scoring and Feedback:
  - After typing each sentence, feedback is provided. The code keeps track of correct sentences and calculates the total score.
  - The elapsed time and WPM are computed to give a measure of typing speed and accuracy.

- Result Display:
  - The results are printed out, including the user’s score, elapsed time, and WPM.
  - The best scores from previous runs are displayed to track and compare performance.

This code provides a typing test that evaluates a user’s typing speed and accuracy. It tracks the best scores across different test runs and provides feedback on performance.
