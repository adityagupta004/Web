@media query(max-width:400px)
body{{
background: blue;
}
}
html,
body {
  min-width: 290px;
  color: #4d4e53;
  background-color: #9999ff;
  font-family: 'Open Sans', Arial, sans-serif;
  line-height: 1.5;
}

#navbar {
  position: fixed;
  min-width: 290px;
  top: 0px;
  left: 0px;
  width: 300px;
  height: 100%;
  border-right: solid;
  border-color: black
}

header {
  color: black;
  margin: 10px;
  font-family:allura;
  text-align: center;
  font-size: 1.8em;
  font-weight: thin;
  background-color: #9999ff;
}

#main-doc header {
  text-align: left;
  margin: 0px;
  
}

#navbar ul {
  height: 82%;
  padding: 0;
  overflow-y: auto;
  overflow-x: hidden;
}

#navbar li {
  color: black;
  border-top: 1px solid;
  list-style: none;
  position: relative;
  width: 100%;
}

#navbar a {
  background-color: #D3D3D3;
  display: block;
  padding: 10px 30px;
  color: purple;
  text-decoration: none;
  cursor: pointer;
}

#main-doc {
  position: absolute;
  margin-left: 310px;
  padding: 20px;
  margin-bottom: 110px;
}

section article {
  color: #4d4e53;
  margin: 15px;
  font-size: 0.96em;
}

section li {
  margin: 15px 0px 0px 20px;
}

code {
  display: block;
  text-align: left;
  white-space: pre-line;
  position: relative;
  word-break: normal;
  word-wrap: normal;
  line-height: 2;
  background-color: #9999ff;
  padding: 15px;
  margin: 10px;
  border-radius: 15px;
}

@media only screen and (max-width: 815px) {
  /* For mobile phones: */
  #navbar ul {
    border: 1px solid;
    height: 207px;
  }

  #navbar {
    background-color: white;
    position: absolute;
    top: 0;
    padding: 0;
    margin: 0;
    width: 100%;
    max-height: 275px;
    border: none;
    z-index: 1;
    border-bottom: 2px solid;
  }

  #main-doc {
    position: relative;
    margin-left: 0px;
    margin-top: 270px;
  }
}

@media only screen and (max-width: 400px) {
  #main-doc {
    margin-left: -10px;
  }

  code {
    margin-left: -20px;
    width: 100%;
    padding: 15px;
    padding-left: 10px;
    padding-right: 45px;
    min-width: 233px;
  }
}
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" >
  </head>
   
  <body>
    <nav id="navbar">
      <header>RICH DAD POOR DAD</header>
      <h5 style=" text-align:center;color: gray;">-Robert T. Kiyosaki</h5>
      <ul>
        <li><a class="nav-link" href="#Introduction">Introduction</a></li>
        <li>
          <a class="nav-link" href="#What_you_should_already_know"
            >Rich don't work for money</a
          >
        </li>
        <li>
          <a class="nav-link" href="#JavaScript_and_Java"
            >Why Teach Financial Litracy</a
          >
        </li>
        <li><a class="nav-link" href="#Hello_world">Mind Your Own Business</a></li>
        <li><a class="nav-link" href="#Variables">The History Of Taxes </a></li>
        <li>
          <a class="nav-link" href="#Declaring_variables"
            >The Rich Invent Money</a
          >
        </li>
        <li><a class="nav-link" href="#Variable_scope">Work to Learn</a></li>
        <li>
          <a class="nav-link" href="#Global_variables">Overcomming Obstacles</a>
        </li>
        <li><a class="nav-link" href="#Constants">Getting Started</a></li>
        <li><a class="nav-link" href="#Data_types">Still Want More?</a></li>
        <li>
          <a class="nav-link" href="#if...else_statement"
            >Final Thoughts</a
          >
        </li>
        <li><a class="nav-link" href="#while_statement">Study Session </a></li>
        <li>
          <a class="nav-link" href="#Function_declarations"
            >About the Author</a
          >
        </li>
        <li><a class="nav-link" href="#Reference">Reference</a></li>
      </ul>
    </nav>
    <main id="main-doc">
      <section class="main-section" id="Introduction">
        <header>Introduction</header>
        <article>
          <p>
           I had two fathers, a rich one and a poor one. One was highly
educated and intelligent. He had a Ph.D. and completed four years
of undergraduate work in less than two years. He then went on to
Stanford University, the University of Chicago, and Northwestern
University to do his advanced studies, all on full financial scholarships.
The other father never finished the eighth grade.
          </p>

          <p>
            Both men were successful in their careers, working hard all their
lives. Both earned substantial incomes. Yet one always struggled
financially. The other would become one of the richest men in
Hawaii. One died leaving tens of millions of dollars to his family,
charities, and his church. The other left bills to be paid.
          </p>
       
            </li>
          </ul>
        </article>
      </section>
      <section class="main-section" id="What_you_should_already_know">
        <header>Rich don't work for money</header>
        <article>
          <p>The poor and the middle class work for money.
The rich have money work for them.</p>

          
             
            
        </article>
      </section>
      <section class="main-section" id="JavaScript_and_Java">
        <header>Why Teach Financial Litracy</header>
        <article>
          <p>
            It’s not how much money you make.
It’s how much money you keep.</p>

          <p>
            In 1990, Mike took over his father’s empire and is, in fact,
doing a better job than his dad did. We see each other once or twice
a year on the golf course. He and his wife are wealthier than you
could imagine. Rich dad’s empire is in great hands, and Mike is now
grooming his son to take his place, as his dad had groomed us.
In 1994, I retired at the age of 47, and my wife Kim was 37.
Retirement does not mean not working. For us, it means that, barring
unforeseen cataclysmic changes, we can work or not work, and our
wealth grows automatically, staying ahead of inflation. </p>
          
        </article>
      </section>
      <section class="main-section" id="Hello_world">
        <header>Mind Your Own Business</header>
        <article>
          The rich focus on their asset columns while
everyone else focuses on their income statements.
      
        </article>
      </section>
      <section class="main-section" id="Hello_world">
        <header>The History of Taxes</header>
        <article>
         My rich dad just played the game smart,
and he did it through corporations—
the biggest secret of the rich
<p>I remember in school being told the story of Robin Hood and
his Merry Men. My teacher thought it was a wonderful story of a
romantic hero who robbed from the rich and gave to the poor. My rich
dad did not see Robin Hood as a hero. He called Robin Hood a crook.
Robin Hood may be long gone, but his followers live on. I often
still hear people say, “Why don’t the rich pay for it?” or “The rich
should pay more in taxes and give it to the poor.”</p>
      
        </article>
      </section>
      <section class="main-section" id="Variables">
        <header>The Rich Invent Money</header>
        <p>
         Often in the real world, it’s not the smart
who get ahead, but the bold.

        </p>
        <p>
          You can play CASHFLOW
Classic on the web at
www.richdad.com and
learn how money works.
<br>
<br>
Last night, I took a break from writing and watched a TV
program on the history of a young man named Alexander Graham
Bell. Bell had just patented his telephone and was having growing
pains because the demand for his new invention was so strong.
Needing a bigger company, he then went to the giant at that time,
Western Union, and asked them if they would buy his patent and
his tiny company. He wanted $100,000 for the whole package. The
president of Western Union scoffed at him and turned him down,
saying the price was ridiculous. The rest is history. A multi-billiondollar industry emerged, and AT&T was born
        </p>

        
      </section>
      <section class="main-section" id="Declaring_variables">
        <header>Work to Learn</header>
        <article>
         Job security meant everything to my educated dad.
Learning meant everything to my rich dad
          <p>
           A few years ago, I granted an interview with a newspaper in
Singapore. The young female reporter was on time, and the interview
got under way immediately. We sat in the lobby of a luxurious hotel,
sipping coffee and discussing the purpose of my visit to Singapore.
I was to share the platform with Zig Ziglar. He was speaking on
motivation, and I was speaking on “The Secrets of the Rich.”
          </p>
          <p>
            “Someday, I would like to be a best-selling author like you,” she
said. I had seen some of the articles she had written for the paper, and
I was impressed. She had a tough, clear style of writing. Her articles
held a reader’s interest.
          </p>
          <p>
           “You have a great style,” I said in reply. “What holds you back
from achieving your dream?”
          </p>
        </article>
      </section>
      <section class="main-section" id="Variable_scope">
        <header>Overcomming Obstacles</header>
        <article>
          <p>
          The primary difference between a rich person
and a poor person is how they manage fear.
          </p>

          <p>
           Once people have studied and become financially literate, they may
still face roadblocks to becoming financially independent. There are
five main reasons why financially literate people may still not develop
abundant asset columns that could produce a large cash flow. The five
reasons are:
          </p>
       
          <p>
           1. Fear<br>
2. Cynicism<br>
3. Laziness<br>
4. Bad habits<br>
5. Arrogance
          </p>

        
          >
        </article>
      </section>
      <section class="main-section" id="Global_variables">
        <header>Getting Started</header>
        <article>
          <p>
            There is gold everywhere.
Most people are not trained to see it.
          </p>

          <p>
            I wish I could say acquiring wealth was easy for me, but it wasn’t.
So in response to the question “How do I start?” I offer the thought
process I go through on a day-to-day basis. It really is easy to find
great deals. I promise you that. It’s just like riding a bike. After a little
wobbling, it’s a piece of cake. But when it comes to money, it takes
determination to get through the wobbling. That’s a personal thing.
          </p>
        </article>
      </section>
      <section class="main-section" id="Constants">
        <header>Still Want More?</header>
        <article>
          <p>
         Many people may not be satisfied with my 10 steps. They see
them more as philosophies than actions. I think understanding the
philosophy is just as important as the action. There are many people
who want to do instead of think, and then there are people who think
but do not do. I would say that I am both. I love new ideas, and I
love action.
          </p>

         
          <p>
           So for those who want a to-do list on how to get started, I will
share with you some of the things I do, in abbreviated form.
          </p>

          <p>
            Stop doing what you’re doing. In other words, take a break and
assess what is working and what is not working. The definition
of insanity is doing the same thing over and over and expecting
a different result. Stop doing what is not working, and look for
something new
          </p>

          <p>
            Look for new ideas. For new investing ideas, I go to bookstores
and search for books on different and unique subjects. I call
them formulas. I buy how-to books on formulas I know
nothing about.
          </p>
        </article>
      </section>
      <section class="main-section" id="Data_types">
        <header>Final Thoughts</header>
        <article>
          <p>I would like to share some final thoughts with you.
The main reason I wrote this book, and the reason it has remained
a bestseller since 2000, was to share insights into how increased financial
intelligence can be used to solve many of life’s common problems. Without
financial training, we all too often use the standard formulas to get through
life: Work hard, save, borrow, and pay excessive taxes. Today, more than
ever, we need better information.</p>
        </article>
      </section>
      <section class="main-section" id="if...else_statement">
        <header>Study Session</header>
        <article>
         
          <p>
           All of you were given two great gifts: your mind and your time.
It is up to you to do what you please with both. With each dollar bill
that enters your hand, you, and only you, have the power to determine
your destiny. Spend it foolishly, and you choose to be poor. Spend it
on liabilities, and you join the middle class. Invest it in your mind and
learn how to acquire assets, and you will be choosing wealth as your
goal and your future. The choice is yours, and only yours. Every day
with every dollar, you decide to be rich, poor, or middle class.
          </p>
        </article>
      </section>
      <section class="main-section" id="while_statement">
        <header>About the Author</header>
        <article>
         Best known as the author of Rich Dad Poor Dad—the #1 personal finance book of
all time—Robert Kiyosaki has challenged and changed the way tens of millions of
people around the world think about money. He is an entrepreneur, educator, and
investor who believes the world needs more entrepreneurs who will create jobs

        
          <p>
            With perspectives on money and investing that often contradict conventional wisdom,
Robert has earned an international reputation for straight talk, irreverence, and courage
and has become a passionate and outspoken advocate for financial education.
          </p>

          <p>
           Robert and Kim Kiyosaki are founders of The Rich Dad Company, a financial
education company, and creators of the CASHFLOW® games. In 2014, the company
will leverage the global success of the Rich Dad games in the launch of a new and
breakthrough offering in mobile and online gaming. 
          </p>

          

          <p>
            Robert has been heralded as a visionary who has a gift for simplifying complex
concepts—
          </p>
          <p>
           Ideas related to money, investing, finance, and economics—
          </p>

          <p>
           To learn more, visit RichDad.com
          </p>
        </article>
      </section>
      <section class="main-section" id="Function_declarations">
        
      <section class="main-section" id="Reference">
        <header>Reference</header>
        <article>
          <ul>
            <li>
             Rich dad said, “Ordinary earned income is money you work for,
and passive and portfolio income is money working for you.” Knowing
that little difference has been significant in my life. Or, as Robert Frost
ends his poem, “And that has made all the difference.”

              <a
                href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide"
                target="_blank"
                >RICH DAD POOR DAD</a
              >
            </li>
          </ul>
        </article>
      </section>
    </main>
  </body>
</html>
