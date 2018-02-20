# Queriosity: Automated Data Exploration [[PDF]](http://daslab.seas.harvard.edu/projects/queriosity/assets/doc/queriosity_vision_paper.pdf)

> Data exploration, the process
of sifting through data to extract meaningful information, is
inherently hard as we do not always have a clear idea of what
we are looking for [4], [11]. Data exploration is analogous to
the search for an interesting haystack, rather than a needle, in
bigger multiple haystacks. In this context, data systems play
a fundamental role; they allow us to store and retrieve data.
Existing data systems, however, are ineffective for haystackin-a-haystack
queries. From a user’s point of view, exploratory
data analysis on existing data systems is an excruciating
game of hit-and-trial, which involves several iterations of data
retrieval and analysis to decide what is interesting. [...] (Section I. Paragraph 2)

> Exploration and curiosity are widely
studied notions in artificial intelligence and machine learning
within computer science, as well as in other fields such as
neuroscience and behavioral psychology. The major focus has
been to study and design systems that make sense of an
alien and dynamic environment. The growing data landscape
presents analogous problems in a the context of big data
processing. Petabytes of data collected everyday represent an
alien landscape for both users and conventional data systems.
We find analogy between these distinct yet related paradigms.
Queriousity heralds a paradigm shift in data exploration where
the data system is designed to be curious i.e, to inherently
value and conduct data exploration. (Section I. Paragraph 7)

> [...] to achieve autonomy, a system should
be designed, from the ground up, to work without human
intervention. To achieve learning, a system should be designed,
from the ground up, to autonomously search a big search space
while continuously logging and taking into account incoming
user preferences. To achieve usability a system should be
designed, from the ground up to provide results in the form
of interactive insights. [...] (Section II. Paragraph 1)

> [...] the exploration plane uses past user decisions
and analyses to anticipate future exploration patterns. It can
then interact with the rest of the system and orchestrate a
set of exploratory operations such as discovering interesting
statistical properties or exploring other areas of the data set. As
a result, next time when users are ready to receive information,
Queriosity will be in a better shape to provide it to them. (Section II. Paragraph 4)

> [...] a system that
learns both from user interactions and explored data, requires
a formulation of learning in the context of data exploration.
A typical unsupervised learner proceeds by observing its
environment, trying out actions and accumulating rewards. An
unsupervised learner with no prior knowledge about the surrounding
environment tries out a set of, possibly, randomized
actions and converges to a near-optimal exploration strategy.
As a first step, these actions as well as associated rewards
need to be defined in the context of data exploration. [...] (Section II. Paragraph 8)

> [...] Learning from user interactions ensures a progressively personalized
data system and is important because the user’s past
interactions with the systems are used as an information to
facilitate their future interactions. Along the other dimension,
learning about the data results in a richer understanding of the
data set and is important because it makes the system more
efficient. (Section II. Paragraph 11)
