Name: Pavan Kusampudi
700#: 700762366

## Q5: Evaluation Metrics from a Multi-Class Confusion Matrix

This program takes a table (confusion matrix) that shows how the system classified Cats, Dogs, and Rabbits compared to the correct answers.

For each class:

It looks at how many times the system got it right (true positives).

It also checks how many times the system said “Cat” when it wasn’t actually a cat (false positives).

And how many times it missed a cat when it should have said “Cat” (false negatives).

Using these numbers, it calculates precision (when the system says “Cat,” how often is it correct?) and recall (out of all real Cats, how many did it find?).

Then it combines the results in two ways:

Macro average: takes the simple average across Cat, Dog, and Rabbit — treating each class equally.

Micro average: adds everything up first and then calculates the score — this way bigger classes have more influence.

At the end, it prints all the precision and recall values, both per class and overall.

## Q8. Programming: Bigram Language Model Implementation (based on “Activity: I love NLP corpus” slide)

This program learns from three short training sentences like “I love NLP” and “I love deep learning.”

It counts how often each word appears by itself (unigrams) and how often each pair of words appears together (bigrams).

From this, it learns probabilities like:

If you see “I love,” how likely is the next word “NLP” or “deep”?

It has a function to calculate the probability of a whole sentence by multiplying these bigram probabilities together.

Then it tests two sentences:

“I love NLP”

“I love deep learning”

It works out the probability for each.

“I love NLP” ends up with a higher probability (1/3).

“I love deep learning” has a lower probability (1/6).

Finally, it prints out the counts, the probabilities, the sentence scores, and clearly says that the model prefers “I love NLP” because that word sequence was seen more strongly in training.
