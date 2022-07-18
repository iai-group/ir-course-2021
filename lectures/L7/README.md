# L7: Entity-oriented search part II: Entity linking

In the second module of the entity-oriented search series we look at the task of entity linking: recognizing entity mentions in text and linking them to the corresponding entries in a knowledge base.  We present the canonical pipeline architecture of entity linking systems, and each of its components in detail.  Finally, we discuss evaluation criteria and measures for this task.

## Lecture videos and slides

| **Module** | **Topic** | **Lecture material** |
| -- | -- | -- | 
| L7-1 | Entity linking | **TODO** [slides]() |

## Reading


  * Entity-Oriented Search (Balog) [PDF](https://rd.springer.com/content/pdf/10.1007%2F978-3-319-93935-3.pdf)
    - Chapter 5, until 5.6 (inclusive) + Section 5.8.1



## Summary

Key concepts in this lecture:

  * The entity linking task
  * Canonical entity linking architecture and main components (mention detection, candidate selection, disambiguation)
  * Entity surface form dictionary and its construction from Wikipedia
  * Filtering mentions (keyphraseness and link probability)
  * Candidate selection using commonness
  * Disambiguation approaches and strategies
  * Prior importance features (incl. keyphraseness, link probability, commonness, link prior, page views)
  * Contextual features
  * Contextual similarity
  * Entity-relatedness features (incl. WSM, a.k.a. relatedness)
  * TAGME method
  * AIDA algorithm
  * Evaluation with perfect/relaxed match, evaluation measures
