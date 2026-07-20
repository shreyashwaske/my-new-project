# StudySmart

Building AI course project

## Summary

StudySmart is an AI-powered study-planning assistant for students. It uses quiz results, study time, assignment performance, and upcoming deadlines to identify topics that may need extra attention and recommend what to study next.

## Background

Students often have many subjects, deadlines, and learning materials to manage. It can be difficult to know which topic should be revised first or how much time to spend on each subject.

This project aims to support students by offering personalized study recommendations. Better planning can reduce stress and help students use their study time more effectively.

## How is it used?

A student voluntarily provides information such as quiz and assignment scores, subjects studied, study time, and upcoming deadlines. The system analyzes the information and recommends a study plan.

For example, it may suggest revising mathematics because recent quiz scores are lower than in other subjects and an exam is approaching. Students can accept, ignore, or change the recommendations.

## Data sources and AI methods

The project would use data that students choose to provide, such as study logs, quiz scores, and deadlines. A real implementation should protect student privacy and collect only the minimum data needed.

Possible AI methods include:

* regression to estimate expected performance
* classification to identify topics where a student may need support
* recommendation methods to suggest the next topic or activity
* nearest-neighbor methods to identify similar study patterns

A first prototype could use anonymous or simulated data rather than real student records.

## Challenges

StudySmart does not replace teachers, tutors, or the student's own decisions. Test scores do not fully represent a student's ability, motivation, or circumstances.

Important challenges include protecting personal data, avoiding biased recommendations, making recommendations understandable, and ensuring the tool supports students instead of creating pressure.

## What next?

The next step would be to interview students and teachers to learn what recommendations would be most helpful. After that, I could build a small prototype with simulated data and test whether its suggestions are useful.

Future versions could include calendar integration, progress charts, and optional teacher feedback.

## Acknowledgments

* This project was created for the Building AI course.
* The project structure follows the Building AI final-project README template by Reaktor Innovations and the University of Helsinki.
