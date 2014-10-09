#2014 Nickel City Ruby Notes
Buffalo, NY
October 3rd and 4th


####Codecation - Ben Orenstein
- Choose someone awesome.
- Go some place.
- Spend bulk of time writing code.
- Ship something.
- Keep a daily journal and reflect on it (Trailmix.life)
- This is a Profession where you can play, so find time to enjoy it.


####Multitudes - Sarah Mei
- Two personalities in the ruby land: Application devs, and Gem devs.
- At one of Sandy Metz's (POODR) first talks, Jim Weirch (rake and gem) said he absolutely disagreed that people should always use attr_readers instead of accessing instance variables directly.
- Jim Weirich wrote gems, Sandy Metz wrote applications. These are not sides or camps, these are spectrums, and we move between them in different situations.
- How do I start contributing to open source, if open source is mostly gems, and I'm an application developer?
- We need both, and they are different skills. Be intentional about learning them.


####Aesthetics and the Evolution of Code - Coraline Ehmke
- Elegance in language
  - Correctness - does it work?
  - Performance - speed is a relative thing.
  - Brevity - short code.
  - Readability - subjective.
- Ruby is a tight second to Python on this highly scientific scale that she made up.
- MVP stands for most evil products. Asks audience to not write code for the devil.
- Code we write is an expression of our intellect and selves.
- Aesthetic appeal is an important quality.


####How to be an awesome junior developer (and why to hire them) - Eric Stiens
- To Mentors: Don't use their keyboard because you are impatient or frustrated.
- Common mistakes mentors make in code reviews:
  - Too specific. Writing code for someone can be like taking the keyboard away.
  - Not specific enough. Example: "This needs to be refactored"
  - Too mean or terse. Often due to laziness.
  - Focusing too much on inconsequential design choices. Nitpicks are good, just not all the time.
- Examples of helpful code review comments:
  - "Great job on ... but you could probably refactor x and y into another object."
  - "We probably need some testing on this."
  - "A more idiomatic way of doing this is..."
  - "You should look into this rails method here, it does what you want."
  - "What will happen if we pass nil into this method?"
- Diversity does not equal social justice. Desegregation is not the same as integration.


####How to NOT be an Expert - Jen Meyers
- Many experts are stereotypically seen as unfallable.
- The idea of "Don't speak up unless you are right" is holding people back from learning.
- We should redefine experts to be questioners, explorers, learners, beginners, fuck-ups, risk takers.
- Remind yourself what it means to learn new things, do new things all of the time.
- Support other people in their own journey of trying new things.
- Always question the goals that you're going for.


####Concurrency for !Dummies (Who Don't Get It (...Yet)) - Kerri Miller
- The example of philosophers eating spaghetti is a model of handling processes.
- An example of concurrency is preparing Thanksgiving meal, where all dishes need to be cooked by a certain time, there are limited resources, and conflicting needs.
- Concurrency != Parallelism
- Matz recently said that looking back he would remove threads and allow concurrency.
- concurrency can melt your brain
- it behaves diff than you expect
- it requires diff thinking
- it needs new patterns and abstractions
- What do other languages offer?
- Actor pattern (erlang and scala) don't share memory state with other actors. They send messages to each other (OOD like)
- Reactor pattern (Ember, Angular). Node is doing soul searching, it can spiral nasty really fast in a branch - lots of work. Forces you how to change how you write code. Diff structure.
- Channels (Go). Kind of like an Actor. If house was on fire, you would call channel (911), not each of the firefighters (actors). Service calls, full fledged applications on their own. Very OO
- Concurrency isn't lowest hanging fruit (garbage collection can come first).
- You should learn it because things will change. start experimenting, get started.


####Learning from Failure - Meagan Waller
- Document problem solving approach.
- Premortem new projects. Given a scenario where the project failed. Share why the failure happened. This reduces overconfidence, and can liberate people who are afraid to speak out.
- Talk about failure and empower others.
- Example praise: "Thanks for submitting your code, I appreciate how hard you worked it."
- If you praise effort instead of intelligence, then people are not going to be afraid of learning.
