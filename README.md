# Multiple_choice
Write a program that a teacher can use to grade one multiple choice test.

Problem ccc11s2 from DMOJ

"Your teacher likes to give multiple choice tests. One benefit of giving these tests is that they are easy to mark, given an answer key. The other benefit is that students believe they have a one-in-five chance of getting the correct answer, assuming the multiple choice possibilities are A, B, C, D or E.

Write a program that your teacher can use to grade one multiple choice test."

Input Specification:
The input will contain the number N (0 < N < 1000) followed by 2N lines. The 2N lines are composed of N lines of student responses (with one of A, B, C, D or E on each line), followed by N lines of correct answers (with one of A, B, C, D or E on each line), in the same order as the student answered the questions (that is, if line "i" is the student response, then line "N+1" will contain the correct answer to that question).

Output Specification:
Output the integer  C(0 ≤ C ≤ N) which corresponds to the number of questions the student answered correctly.
