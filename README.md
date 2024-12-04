java c
Problem   Set   4
ECO3121   -   Fall   2024
Due   3   PM,   December   11,   2024
No   late   submission   is   allowed
Please combine your answer, Stata code and   requested   output   in   one   pdf   ﬁle and upload it to   Blackboard
Question   1A   researcher   is   interested   in   analyzing   the   efect   of   a   free   fertilizer   policy   on   crop   yield.   He   has   a   panel   data   set   for   1000   villages   in   rural   China   over   2016   to   2019   in   which   the   data for the   average crop yield   (Yit   )   in village   (entity)   i in   (time)   year   t   and   the   indicator   for   whether   the   village   participate   in   this   free   fertilizer   program   (Xit   )   are   available.
1.    He   considers   the   following   panel   model:
Yit      = β1   Xit   + αi   +   uitwhere   αi    are   i.i.d.    unobserved   random   variables   and   αi    is   correlated   with   Xit.    (a)   Explain   how   the   researcher   should   estimate   β1      with   the   data   he   has.    (b)   Provide   a   factor   that   is   modelled   by   αi.    (2   points)
2.    He   considers   the   following   panel   model:
Yit      = β1   Xit   +   √t   + uitwhere   √t    are   i.i.d.    unobserved   random   variables   and   √t    is   correlated   with   Xit.    (a)   Explain   how   the   researcher   should   estimate   β1      with   the   data   he   has.    (b)   Provide   a   factor   that   is   modelled   by   √t.    (2   points)
3.    He   considers   the   following   panel   model:
Yit      = β1   Xit   + αi   +   √t   + uit
What   is   the   advantage   of this   model   compared   to   the   above   two?    (2   points)
4.    The ﬁxedefects estimator of β1   in   (3) can be obtained by applying two-way demean   on this model.    The ﬁrst is   entity-demean   ignoring   the   time   ﬁxed-efects   followed   by the   time-demean   ignoring   the   entity-ﬁxed   efects.      Assume   the   panel   is   balanced.
Show   that   the   order   of demean   is   unimportant   (either   starting   with   entity-demean   or   time-demean   doesn’t   matter).      Give   an   intuitive   explanation   for   why.    (3   points)
Question   2Following   a   national   poverty   alleviation   program   in   Gansu   province,   in   July   2017,   many   households   in   Gansu   province   received   subsidy   and   ﬁnancial   support.    Thus,   this   policy   experiment induced a geographical allocation   of subsidy   that   can   be   presumed   exogenous   in an income growth. Let Yi0 and Yi1 denote the consumption   in   village   i before   and   after   the   policy   intervention. Let   Di be   a   dummy   variable   that   takes   the   value   1   if household   i   is      in Gansu   province, 0   otherwise (other   provinces).       We   would      like   to   estimate   the   treatment   efect   of   the   income   change   on   consumption   with   the   diference-in-diference   estimator.
1.    (2 points) Write down this diference-in-diference estimator as a function of {Yi0   ,   Yi1   ,   Di   }   for   i   =   1,   ...,   n.
2.    (2 points) What is the key assumption for this estimator to bean unbiased estimator   of the   treatment   efect?
3.    (2 points) Suppose after the policy intervention, households in Gansu province works   harder      (policy   irrelevant)   and   thus   higher   income   and   consumption   are   expected.   Does the diference-in-diference estimator under or over estimate the treatment   efect.      Explain.
Question   3
We are going to replicate a study conducted by   Card   and   Krueger   in   1994 that   investigate   the   relationship   between   a   rise   in   minimum   wage   and 代 写ECO3121 - Fall 2024 Problem Set 4
代做程序编程语言  employment.Economic   theories   have   long   suggested   that   increases   in   the   minimum   wage   lead   to   a   reduction   in   the   employment   for   at   least   two   reasons:    Businesses   are   less   likely   to   hire   and   will   rather   invest   in   other   resources   that   are   now   cheaper   because   of wage   increase.   Higher   salaries   will   induce   businesses   to   raise   their   prices   to   compensate   their   greater   costs;   as   prices   increase,   we   expect   fewer   buyers,   which   will   lead   to   lower   demand   and   employment.These   theories   have   found   mixed   support   but   the   discussion   is   still   very   much   open   within   the   policy   world,   as   states   discuss   the   opportunity   to   rise   their   minimum   wage   to   help local populations to face increasing living costs.    Discussions are currently occuring in   New Jersey and Illinois to raise the minimum wage to   15$/hour   (New york has successfully   passed   this   same   raise   in   2018).One   of the   ﬁrst   study   looking   at   this   policy   problem   was   Card   and   Krueger’s.    They   applied a diference-in-diference the design to look at two   groups   of fast-food restaurants:   fast-food   restaurants   in   New   Jersey   where   the   minimum   wage   increased   from   4.25$   to   5.05$   per   hour   (treatment   group)   AND   fast-food   restaurants   in   Pennsylvania   where   the   minimum   wage   did   not   increase   (control   group).   They   collected   employment   data   before   and   after   the   minimum   wage   was   approved.
Table   1:   Variable   Description
Variable   name
Description
ID
Unique   identiﬁer   for   fast   food
Treatment
Pre-treatment   (=0)   and   post-treatment   (=1)
Group
1   if NJ   (treatment);   0   if PA   (Control)
Empl
#   of full   time   employees
C.Owned
If owned   by   a   company   (=1)   or   not   (=0)
Hours.Opening
Number   hours   open   per   day
Soda
Price   of medium   soda,   including   tax
Fries
price   of small   fries,   including   tax
Chain
1   =   BK,   2   =   KFC,   3   =   Roys,   4   =   Wendys
SouthJ
South   New   Jersey
CentralJ
Central   New   Jersey
NorthJ
North   New   Jersey
PA1
Northeast   suburbs   of Philadelphia
PA2
Easton   and   other   PA   areas
Shore
New   Jersey   Shore
1.    Explain why   a simple comparison in   employment   between   New   Jersey   and   PA   after   the   minimum   wage   policy   may   not   be   a   good   estimation   for   the   treatment   efect.   (2   points)
2.      What   is   the   regression   model   you’d   like   to   estimate?    (2   points)
3.      What   is   the   key   assumption   of the   estimation   method   you   use?    (1   point)
4.    The data is in the   blackboard   (bb)   Assignment   4   ﬁle   folder   titled   DID   Example.   csv,   and the variables   are   deﬁned   as   in   Table   1.    Run the regression   model you   proposed   in   2,   and   report   the   regression   results.    (3   points)
(Hint:   You   need   ﬁrst   import   the   csv   ﬁle   into   Stata.
Replace   all      “NA”   with   the   missing   value   in   variables,   using
replace   var   name   =   ””   if var   name   ==   ”NA”
Then,   convert   string   variables   to   numeric   variables,   by   the   “destring”   command.   Please   include   control   variables   that   you   think   necessary.)
5.      Explain why   this   is   an   unbiased   estimation   of the treatment   efect.    (Hint:   You   can   use   a   graph   if necessary)   (2   points)

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
