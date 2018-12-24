[How To Be a Programmer: A Short,Comprehensive, and Personal Summary](https://www.doc.ic.ac.uk/~susan/475/HowToBeAProgrammer.pdf)

by Robert L. Read, published December 16, 2002

The excellent books The Pragmatic Programmer[8], Code Complete[3], Rapid Development[2], and Extreme Programming Explained[4] Paul Graham[6] and Eric Raymond[7]

If there is a single key to debugging is to use the divide and conquer technique on the mystery.

You should do a performance analysis first to find out where the time is really going, and decide what to improve from there. As a rule of thumb you should think carefully before doing anything unless you think it is going to make the system or a significant part of it at least twice as fast. There is usually a way to do this.

The intermittent bug is a cousin of the 50-foot-invisible-scorpion-from-outerspace kind of bug. This nightmare occurs so rarely that it is hard to observe, yet often enough that it can’t be ignored. You can’t debug because you can’t find it. Try, try, try to reproduce it. If you can’t reproduce it, set a trap for it by building a logging system, a special one if you have to, that can log what you guess is what you need when it really occurs. If the bug only occurs in production, this is a long process. Each hint that you get from the log about what the problem may be may not provide the solution but suggest the need for more logging. The new logging may take a long time to be put into production. Then you have to wait for the bug to occur to get more information. This cycle can go on for some time.

Respect every person’s time, and balance it against your own. Asking someone a question accomplishes far more than just receiving the answer. The person learns about you, both by enjoying your presence and hearing the particular questions. You learn about the person in the same way, and you may learn the answer you seek. This is usually far more important than your question.

The basic rule is that everyone benefits from talking to you a little bit, and the more they talk to you the less benefit they derive. It is your job to provide them this benefit, and to get the benefit of communicating with them, keeping the benefit in balance with the time spent.

You should ask people for a little bit of their wisdom and judgment whenever you honestly believe they have something to say. This flatters them and you will learn something and teach them something. A good programmer does not often need the advice of a Vice President of Sales, but if she ever does, she should be sure to ask for it.

When it comes to actually documenting code itself, as opposed to producing documents that can actually be read by non-programmers, the best programmers I’ve ever known hold a universal sentiment: write self-explanatory code and don’t document code except in the places that you cannot make it clear.

This is a good time to document, even if it is only for yourself, because the act of trying to document the code will force you to consider angles you might not have considered, and the resulting document may be useful. While you’re doing this, consider what it would take to rewrite some or all of the code. Would it actually save time to rewrite some of it? Could you trust it better if you rewrote it? Be careful of arrogance here. If you rewrite it, it will be easier for you to deal with, but will it really be easier for the next person who has to read it? If you rewrite it, what will the test burden be? Will the need to re-test it outweigh any benefits that might be gained?

It is important to remember that abstraction and encapsulation, two of the programmers best tools, are particularly applicable to lousy code. You may not be able to redesign a large block of code, but if you can add a certain amount of abstraction to it you can obtain some of the benefits of a good design without reworking the whole mess. In particular, you can try to wall off the parts that are particularly bad so that they may be redesigned independently.

• communicate as much as possible with everyone in the company so that no one can mislead the executives about what is going on, • learn to estimate and schedule defensively and explicitly and give everyone visibility into what the schedule is and where it stands, • learn to say no, and say no as a team when necessary, and • quit if you have to

Programmers have to work together as a team. When disagreement arise, it must be resolved somehow, it cannot be ducked for long. Difficult people often are extremely intelligent and have something very useful to say. It is critical that one listen and understand the difficult person without prejudice caused by the person. A failure to communicate is often the basis of disagreement and it can sometimes be removed with great patience. Try to keep this communication cool and cordial, and don’t accept any baits for greater conflict that may be offered. After a reasonable period of trying to understand, make a decision.

It is a wonderful and surprising fact that programmers are highly motivated by the desire to create artifacts that are beautiful, useful, or nifty. This desire is not unique to programmers nor universal but it is so strong and common among programmers that it separates the them from others in most companies. This has practical and important consequences. If programmers are asked to do something that is not beautiful, useful, or nifty, they will have low morale. There’s a lot of money to be made doing ugly, stupid, and boring stuff; but in the end fun will make the most money for the company.

Try to get your boss to let you have formal training, but understand that it often no better than the same amount of time spent simply playing with the new skill you want to learn. It is however, easier to ask for training than playtime in our imperfect world, even though a lot of formal training is just sleeping through lectures waiting for the dinner party.

Don’t forget that the most important skills for a programmer are not the technical ones. Give your people a chance to play and practice courage, honesty, and communication.

A project often depends on software produced by organizations that it does not control. There are great risks associated with third party software that must be recognized by everyone involved. Never, ever, rest any hopes on vapor. Vapor is any alleged software that has been promised but is not yet available. This is the surest way to go out of business. It is unwise to be skeptical of a software company’s promise to release a certain product with a certain feature at a certain date; it is far wiser to ignore it completely and forget you ever heard it. Never let it be written down in any documents used by your company. If third party software is not vapor, it is still risky, but at least it is a risk that can be tackled. If you are considering using third party software you should devote energy early to evaluating it. People might not like to hear that it will take two weeks or two months to evaluate each of three products for suitability. But it has to be done as early as possible. The cost of integrating cannot be accurately estimated without a proper evaluation.

Disagreement is a great opportunity to make a good decision, but it should be
handled delicately. Hopefully you feel that you have expressed your thoughts
adequately and been listened to before the decision is made. In that case there
is nothing more to say, and you should decide whether you will stand behind
the decision even thought you disagree with it. If you can support this decision
even though you disagree, say so. This shows how valuable you are because you
are independent and not a yes-man, but respectful of the decision and a team
player

Usually, this is not a problem. In some stressful circumstances and with
some personality types this can lead to things being taken personally. For
instance, some very good programmers lack the confidence needed to challenge
a decision even when they have good reason to believe it to be wrong. In the
worst of circumstances the decision maker is insecure and takes it as a personal
challenge to her authority. It is best to remember in such circumstances that
people react with the reptilian part of their brains. You should present your
argument in private, and try to show how new knowledge changes the basis on
which the decision was made. Whether the decision is reversed or not, you must remember that probably
no one will ever have a right to say ”I told you so!” since the other decision will
not have been fully explored.

6.3 How to Decide If Software Is Too Immature
The use of software other people wrote is one of the most effective ways to build
quickly a solid system. It should not be discouraged, but the risks associated
with it must be examined. One of the biggest risks is the period of bugginess
and near inoperability that is often associated with software before it matures
through usage into a usable product. When considering integrating with or
becoming dependent in some way on a software system, whether created in
house or by a third party, it is very important to consider if it is really mature
enough to be used. Here are some questions you should ask yourself about it:
• Is it vapor? (Promises are very immature).
• Is there an accessible body of lore about the software?
• Are you the first user?
• Is there a strong incentive for continuation?
• Has it had a maintenance effort?
• Will it survive defection of the current maintainers?
• Is there a seasoned alternative at least half as good?
• Is it known to your tribe or company?
• Is it desirable to your tribe or company?
• Can you hire people to work on it even if it is bad?

Assume responsibility in excess of your authority. Play the role that you desire. Express appreciation for people’s contribution to the success of the larger
organization, as well as things as that help you personally.
If you want to become a team leader, instigate the formation of consensus.
If you want to become a manager, take responsibility for the schedule. You can
usually do this comfortably while working with a leader or a manager, since this
frees her up to take greater responsibility. If that is too much to try, do it a
little at a time.
Evaluate yourself. If you want to become a better programmer, ask someone
you admire how you can become like her. You can also ask your boss, who will
know less but have a greater impact on your career.
Plan ways to learn new skills, but the trivial technical kind like learning a
new software system and the hard social kind like writing well, by integrating
them into your work.

The three most import considerations for the potential computer science
technique are:
• Is it well encapsulated so that the risk to other systems is low and the
overall increase in complexity and maintenance cost is low?
• Is the benefit startling (for example, a factor of two in a mature system
or a factor of ten in a new system)?
• Will you be able to test and evaluate it effectively?

It is your duty to understand the user, and to help your boss understand the
user. Because the user is not as intimately involved in the creation of your
product as you are, she behaves a little differently:
• The user generally makes short pronouncements.
• The user has her own job; she will mainly think of small improvements in
your product, not big improvements.
• The user can’t have a vision across all the users of your product.
It is your duty to give them what they really want, not what they say the
want. It is however, better to propose it to them and get them to agree that
your proposal is what they really want before you begin, but they may not have
the vision to do this. Your confidence in your own ideas about this should vary.
You must guard against both arrogance and false modesty in terms of knowing
what the customer really wants. Programmers are trained to design and create.
Market researchers are trained to figure out what people want. These two kinds
of persons, or two modes of thought in the same person, working harmoniously
together give the best chance of formulating the correct vision.
The more time you spend with users the better you will be able to understand
or guess what will really be successful. You should try to test your ideas against
them as much as you can. You should eat and drink with them if you can.

You should allow people to fail occasionally and plan for some failure in
your schedule. If there is never any failure, there can be no sense of adventure.
If there are not occasional failures, you are not trying hard enough.

Make it clear to the strong members of your team that you think they are
strong by saying so in public. Praise should be public and criticism private

. You should do what you are best at, but try to
find a way to stretch yourself not by taking on more work but by exercising a new
skill. Leadership and communication skills are more important than technical
skills. If you are very strong, take on the hardest or riskiest task, and do it as
early as possible in the project to decrease risk as much as possible.

To develop team spirit, corny stuff like logoized clothing and parties are good
but not as good as personal respect. If everyone respects everyone else, nobody
will want to let anybody down. Team spirit will be created when people make
sacrifices for the team and they think in terms of the good of the team rather
than their own personal good. As a leader, you can’t ask for more than you
give yourself

Praise often rather than lavishly. Especially praise those who disagree with
you when they are praiseworthy. Praise in public and criticize in private; with
one exception: sometimes growth or the correction of a fault can’t be praised
without drawing embarrassing attention to the original fault, so that growth
should be praised in private.

To gather support for a project, create and communicate a vision that demonstrates real value to the organization as a whole. Attempt to let others share
in your vision creation. This gives them both a reason to support you and
getting the benefit of their ideas. Individually recruit key supporters for your
project. Wherever possible, show, don’t tell. If possible construct a prototype
or a mockup to demonstrate your ideas. A prototype is always powerful but in
software it is far superior to any written description.

To communicate well, you have to recognize how hard it is. It is a skill unto
itself. It is made harder by the fact that the persons with whom you have to
communicate are flawed.

The programmer is a social animal whose survival depends on communication with her team. The advanced programmer is a social animal whose
satisfaction depends on communication with people outside her team.
The programmer brings order out of chaos. One interesting way to do this
is to initiate a proposal of some kind outside the team. This can be done in a
strawman or em white-paper format or just verbally. This leadership has the
tremendous advantage of setting the terms of the debate. It also exposes one
to criticism, and worse, rejection and neglect. The advanced programmer must
be prepared to accept this, because she has a unique power and therefore a
unique responsibility. Entrepreneurs who are not programmers need programmers to provide leadership in some ways. Programmers are the part of the
bridge between ideas and reality that rests on reality.

It would be as rude and unsuccessful
to try to convince them these myths are false as to try to disillusion a devoutly
religious person of their beliefs. For that reason, you should recognize these
myths for what they are:
• More documentation is always better. (They want it, but they don’t want
you to spend any time on it.)
• Programmers can be equated. (Programmers vary by order of magnitude.)
• Resources can be added to a project to speed it. (The cost of communication with the new persons is more taxing than helpful.)
• It is possible to estimate software development reliably. (It is not even
theoretically possible.)
Each of these myths reinforces the manager’s idea that they have some actual
control over what is going on. The truth is that managers facilitate if they are
good, and impede if they are bad.
