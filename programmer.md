[How To Be a Programmer: A Short,Comprehensive, and Personal Summary](https://www.doc.ic.ac.uk/~susan/475/HowToBeAProgrammer.pdf)

by Robert L. Read, published December 16, 2002


The excellent books The Pragmatic Programmer[8], Code Complete[3], Rapid Development[2], and Extreme Programming Explained[4] Paul Graham[6] and Eric Raymond[7]

If there is a single key to debugging is to use the divide and conquer technique on the mystery.

You should do a performance analysis first to find out where the time is really going, and decide what to improve from there. As a rule of thumb you should think carefully before doing anything unless you think it is going to make the system or a significant part of it at least twice as fast. There is usually a way to do this.

The intermittent bug is a cousin of the 50-foot-invisible-scorpion-from-outerspace kind of bug. This nightmare occurs so rarely that it is hard to observe, yet often enough that it can’t be ignored. You can’t debug because you can’t find it. Try, try, try to reproduce it. If you can’t reproduce it, set a trap for it by building a logging system, a special one if you have to, that can log what you guess is what you need when it really occurs. If the bug only occurs in production, this is a long process. Each hint that you get from the log about what the problem may be may not provide the solution but suggest the need for more logging. The new logging may take a long time to be put into production. Then you have to wait for the bug to occur to get more information. This cycle can go on for some time.

Respect every person’s time, and balance it against your own. Asking someone
a question accomplishes far more than just receiving the answer. The person
learns about you, both by enjoying your presence and hearing the particular
questions. You learn about the person in the same way, and you may learn the
answer you seek. This is usually far more important than your question.

The basic rule is that everyone benefits from talking to you a little bit, and
the more they talk to you the less benefit they derive. It is your job to provide
them this benefit, and to get the benefit of communicating with them, keeping
the benefit in balance with the time spent.

You should ask people for a little bit of their wisdom and judgment whenever
you honestly believe they have something to say. This flatters them and you will
learn something and teach them something. A good programmer does not often
need the advice of a Vice President of Sales, but if she ever does, she should be
sure to ask for it.

When it comes to actually documenting code itself, as opposed to producing
documents that can actually be read by non-programmers, the best programmers I’ve ever known hold a universal sentiment: write self-explanatory code
and don’t document code except in the places that you cannot make it clear.

This is a good time to document, even if it is only for yourself, because
the act of trying to document the code will force you to consider angles you
might not have considered, and the resulting document may be useful. While
you’re doing this, consider what it would take to rewrite some or all of the code.
Would it actually save time to rewrite some of it? Could you trust it better if
you rewrote it? Be careful of arrogance here. If you rewrite it, it will be easier
for you to deal with, but will it really be easier for the next person who has to
read it? If you rewrite it, what will the test burden be? Will the need to re-test
it outweigh any benefits that might be gained?

It is important to remember that abstraction and encapsulation, two of the
programmers best tools, are particularly applicable to lousy code. You may not
be able to redesign a large block of code, but if you can add a certain amount of
abstraction to it you can obtain some of the benefits of a good design without
reworking the whole mess. In particular, you can try to wall off the parts that
are particularly bad so that they may be redesigned independently.

• communicate as much as possible with everyone in the company so that
no one can mislead the executives about what is going on,
• learn to estimate and schedule defensively and explicitly and give everyone
visibility into what the schedule is and where it stands,
• learn to say no, and say no as a team when necessary, and
• quit if you have to

Programmers have to work together as a team. When disagreement arise, it
must be resolved somehow, it cannot be ducked for long. Difficult people often
are extremely intelligent and have something very useful to say. It is critical that
one listen and understand the difficult person without prejudice caused by the
person. A failure to communicate is often the basis of disagreement and it can
sometimes be removed with great patience. Try to keep this communication
cool and cordial, and don’t accept any baits for greater conflict that may be
offered. After a reasonable period of trying to understand, make a decision.

It is a wonderful and surprising fact that programmers are highly motivated by
the desire to create artifacts that are beautiful, useful, or nifty. This desire is
not unique to programmers nor universal but it is so strong and common among
programmers that it separates the them from others in most companies.
This has practical and important consequences. If programmers are asked
to do something that is not beautiful, useful, or nifty, they will have low morale.
There’s a lot of money to be made doing ugly, stupid, and boring stuff; but in
the end fun will make the most money for the company.
