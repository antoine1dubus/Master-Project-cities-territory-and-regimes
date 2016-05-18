# Master-Project-cities-territory-and-regimes
Master Project


\documentclass[a4paper]{article}

\usepackage[english]{babel}
\usepackage[utf8]{inputenc}
\usepackage{amsmath}
\usepackage{graphicx}
\usepackage[colorinlistoftodos]{todonotes}
\usepackage{amsmath}
\usepackage{graphicx}
\usepackage[colorinlistoftodos]{todonotes}
\usepackage{hyperref}
\usepackage{longtable}                                        
\usepackage{calc}                                             
\usepackage{multirow}                                         
\usepackage{hhline}                                           
\usepackage{ifthen} 
\usepackage{fancyhdr}
\usepackage{pdflscape}
\usepackage{ctable}
\usepackage{placeins}
\usepackage{caption}
\usepackage{chngcntr}
\usepackage{setspace}
\usepackage{cite}
\usepackage{titlesec}
\usepackage{underscore}
\usepackage{changepage}
\usepackage{geometry}
\usepackage{pgfplots}
\usepackage[final]{pdfpages} 
\usepackage[bottom, multiple]{footmisc}
\usepackage{verbatim}
\usepackage{endnotes,etoolbox}

\pgfplotsset{compat=1.12}

\title{Cities, Territories, and Regimes \\
Economic and Political Development in the Holy
Roman Empire}

\author{Antoine Dubus, Rui Guan, Lukas Leucht, Brian Livingston, and Philipp Kastrau}

\date{\today}

\begin{document}
\maketitle

\begin{abstract}
Your abstract.
\end{abstract}

\section{Introduction}
This paper explores the empirical relationship of political stability and long-term economic growth using panel and cross-sectional city-level data from the Holy Roman Empire over a 800-year period. The Holy Roman Empire existed from the 10th until the early 19th century, encompassed most of Central Europe, and was populated by culturally and ethnically diverse groups of people. Even though ruled by one emperor, the Holy Roman Empire is better described as a politically heterogenous collection of small states and cities rather than a single centralised state. Local and regional elites, referred to as the nobility, often held de facto political power within their constituencies (Volckart, 2000). Thus, city-level data can be used to exploit the high variation of political regimes and paths over time to shed light on some possible channels via which political stability could influence long-run economic growth. 

There are three indicators of political stability that can be captured in the data at hand: The length (in years) of a regime at a point in time, the number of (violent and non-violent) regime changes in a given time interval and the number and duration of wars a regime was exposed to in a given time interval. 
This study attempts to measure the direction of the effect any of these three indicators has on long-run growth outcomes and thereby to both test theoretical predictions previous literature has made and contribute to the existing body of empirical evidence on the subject. In particular, we focus on the literature that explored the relationship of political stability and economic growth in the context of autocratic regimes since one expects this relationship to be fundamentally different in democracies rather than autocracies. (Ref?) Cox et al. (2013) claim that reformed states capable of controlling violence and sustained economic growth are mutually necessary for each of them to persist. Olson’s (1993, 2000) idea of a stationary bandit also suggests that a steady long-standing ruler will provide sufficient security for individuals to engage in economic activity and accumulate wealth beyond the subsistence level. Also Alesina (1992) views continuous rule by the same regime as beneficial to the level of certainty agents have regarding the future and thus to economic growth. Other authors (see for example Overland et al. (2005) or Wintrobe (1990)) point out, though, that the relationship between regime length and economic growth may depend on the type of ruler and can  greatly vary amongst autocratic regimes. In terms of the occurrence and duration of wars, even though focussing on 20th century war episodes, most authors find a negative relationship with economic growth (see for example Collier (1999), Alesina et al. (1992), Bodea and Elbadawi (2008), Murdoch and Sandler (2004)). However, the two papers most closely related to the historic context of the Holy Roman Empire suggest there might be overall positive effects of wars on economic growth: Acemoglu et al. (2011) find a positive impact of the French Revolution on conquered territories due to their adoption of better institutions and Voigtländer and Voth (2012) find (?). Regime changes have mostly been found to negatively affect long-run growth (see for example Jones and Olken (2005) and Alesina et al. (1992)).

The paper proceeds as follows: Section 2 provides an overview of past literature and derives theoretical predictions from it. Section 3 describes the data and discusses the empirical strategy adopted. Section 4 gives the main results, conducts several robustness checks and mentions limitations. Section 5 concludes.

\iffalse
\section{Litterature review}
\subsection{Conflicts}

1. Type of War
a) Interstate
- Voth
- Barro
- Cantoni, AJR
b) Civil
- Collier
- Murdoch, Sandler
- Barro

Type of Effects
a) Direct
- Collier: destruction as well
b) Indirect
- Voth
- Collier: mostly (also uncertainty)
- Murdoch, Sandler: negative through disruption and uncertainty
- Barro: property rights
- Cantoni: AJR
c) short run
- Murdoch, Sandler
- Collier: negative
d) long-run
- Mudroch, Sandler: negative
- Voth: positive
- Barro
e) ambigous
- Voth: positive effect
- Cantoni AJR: positive
f) endogenous

2. Regime Change

a) Main effect through uncertainty
b) Other arguments
- Londregan, Poole (1990)
c) Endogeneity
- Londregan, Poole (1990)





\textbf{Voigtländer and Voth (The Three Horsemen of Riches: Plague, War, and Urbanization in Early Modern Europe, 2012)}: explain why European per capita incomes and urbanization
rates increased during the period 1350–1700.
Use a Malthusian model.

Show how shocks on population dynamics may induce a change in steady state, and explain a skip from low expectation western middle age to world domination even before the industrial revolution.

The impact of shocks depend on the nature of the population dynamic and production function, as well as the nature of the shock: affecting cities or rural areas, for instance.

They use China as a way of comparison, and a counter example.

Substantially, demographic shocks are mainly epidemics, for they are relatively frequent and have been extremely intense.

The Malthusian approach is consistent with a middle age/renaissance structure of production, where land is fixed and the main factor of production, implying a decrease of wealth per capita as the population grows.

They find that ``The Black Death was a shock that raised incomes significantly. It killed between one-third and half of the European population in 1348–50. This raised land-labour ratios, and led to markedly higher wages.''

Wars were deadly mainly for they spread epidemics. Trade was also a strong factor of spreading.

Positive impact of war on wealth: wars need taxes, possible if high per capita wealth, possible if negative demographic shocks, that war was inducing thanks to epidemics spreading. (horsemen effect) This positive effect is not diminished by wealth destruction, as the authors argue that war were not capital destructing at this time, but were more acting like ``neutron bombs''.

``Thus, Europe experienced a simultaneous rise in war frequency, in deadly disease outbreaks, and in urbanization''

Not the same effect in China for less wars, more healthy cities.

On our case, what matter is the notion of epidemics spreading: a war, or trade, only have interest as plague (or other) introducing and enhancing. Thus, we should make a distinction between civil wars, invading and being invaded.


\subsubsection{Civil wars}


\textbf{Collier (On the economic consequences of civil war, 1999)}: Impact of civil wars on GDP, focuses in particular on post conflict years (they look at 5 years post conflict). 

Supposedly: negative impact on wealth and institutional solidity of a country, which would imply a post civil war peace dividend. They find that this dividend is contingent to the duration of the war.

They find that during civil wars, the annual growth rate is reduced by 2.2 percents. There comparison between long and short civil wars prove that there is a war overhang effect post short civil wars, while long civil wars are followed by rapid growth, mainly supported by repatriation of previous capital flight. (Probably of limited interest for a region and a period of time where capital flight was not really possible)

Also make a more specific study on which sector is harmed by civil wars, but a physiological approach, pertinent for preindustrial period don't take their results into account.

Civil wars affect the economy in five key ways: destruction, disruption, diversion, dissaving, and portfolio substitution. Disruption refers the disruption caused by warfare and social disorder, such as suppression of civil liberties and a reduction in the efficiency of public services. Diversion concerns the diversion of public expenditure from output-enhancing activities to the army (Bodea and Elbadawi also cover this). Diversion negatively affects the enforcement of contracts. Portfolio substitution is when private agents shift assets out of the country, including human, physical, and financial capital. Civil wars create uncertainty with respect to future asset returns.



\textbf{Blattman, Miguel (Civil War, 2010)}: Build a model to explain the strong correlation between civil wars (at least 1000 battle death in a year) and low growth. They use it to find optimal policies to respond and prevent civil wars.

To note: Daron Acemoglu and James A. Robinson 2006; Niall Ferguson 2002; Charles Tilly 1975; Tilly 1992 claim that war may have a positive impact on growth through war related technological development.
Barro and Sala-i-Martin (2003) human capital destruction has a stronger impact than physical capital; to what extent in our context of very low human capital



\textbf{Engerman: (The Economic Impact of the civil war, 1966)}: 



Side effect we can look at: 

\textbf{Reynal-Querol (Does democracy preempt civil wars?, 2004)}: Is democracy reducing the propensity of civil wars to occur. 

\textbf{Londregan and Poole (Poverty, the coup trap, and the seizure of executive power, 1990)}
Find no systematic effect of coups on the rate of income growth. They suggest this is a result of averaging over a bimodal population wherein the effect of a coup depends on whether the coup faction has pro-growth policies or policies that retard growth. The authors also note that the manner in which the new government comes to power is critical. Revolutions often cause a significant reorganization of society while coups tend to maintain the existing power structure. However, Londregan and Poole observed significant political aftereffects of coups, in that past coups raised the propensity for another coup for up to six years. They also provide evidence that income has a significant coup-inhibiting effect. The authors suggest the presence of common shocks to both income and coups.

\textbf{Alesina et al. (Political instability and economic growth, 1992)}:
Similarly to the findings of Londregan and Poole (1990), authors argue that some regime changes may have positive effects and some negative. If the new government is viewed favorably by economic agents, the uncertainty effect of political instability is lessened. Overall, uncertainty about the policies of a new government hurts productive economic decisions, locally and through foreign investors.

Main results: growth positively correlated to regime stability; strong effect whatever the nature of government change (compare smooth transition to the ones that involve ideological turnover or change in the nature of regime)

On the definition of political stability, they see it as the probability of change in the executive by a constitutional or unconstitutional mean. 

\textbf{Bodea and Elbadawi (Political violence and underdevelopment, 2008)}:
Evidence to suggest that indirect effect on growth is ``substantially larger than the direct capital depletion/destruction effect normally attributed to the onset of political violence.'' Authors reference Collier (1998) with respect to the indirect effects on growth: disruption, diversion, and dissaving.

Note: studies of 20th century conflicts often estimate the likelihood of a regime change either as a control or in order to instrument for the onset of political violence (Alesina et al. 1992, Bodea and Elbadawi 2008, Londregan and Poole 1990). Rodrik (1998) uses proxies of latent social conflict.

\textbf{Murdoch and Sandler (Civil wars and economic growth: spatial dispersion)}:
Estimate that civil wars at home result in significant reductions in short-run and long-run growth. Civil wars in nearby countries result in smaller, but significant reductions in growth. Authors argue that the effect on growth is mostly through uncertainty and disruption of economic activity, not changes in human capital. This is similar to the Bodea and Elbadawi (2008) finding that the indirect costs of civil war outweigh the direct costs.

Relevant for motivation: \textbf{Hausman et al. (Growth accelerations, 2005)} note that growth accelerations tend to be highly unpredictable and unrelated to the standard determinants of growth, even unrelated to most instances of economic reform. However, growth accelerations are often preceded by regime changes. Prior to Hausman et al. were \textbf{Easterly et al. (Good Policy or Good Luck?, 1993)} and \textbf{Pritchett (Understanding patterns of economic growth: searching for hills among plateaus, mountains, and plains, 2000)}. Pritchett argues that the standard econometric approaches to growth didn't apply to developing countries. Developing countries frequently experience wildly unpredictable fluctuations in growth rate; using panel data to capture a trend growth rate is a mistake. The large shifts in growth rates observed in developing countries is often identifiable in episodes. \textbf{Cox, North, and Weingast} claim that the violence trap is the root of all development traps.

\textbf{Collier and Hoeffler (On the economic causes of civil war, 1998)}:
Investigates whether civil wars have economic causes - should look at this more closely, but it looks like a lighter version of the Collier and Hoeffler 2004 paper (below).

\textbf{Hoeffler and Reynal-Querol (Measuring the Costs of Conflict, 2003)}
Investigates costs of civil war. Explains effect of diversion and destruction of resources. Destruction includes infrastructure, civilian population, public services. Main problem of civil war is actually the sever public health consequences after war ends (loss of life from increased spread of disease, etc...).The fear generated by violence is a substantial cost of war. Authors note that civil war is often justified on political grounds "to achieve change for the better." However they argue that "far from being a catalyst for beneficial change, civil war typically leaves a persisting legacy of poverty and misery." Authors here use policy measures adopted by the World Bank to show that policies actually worsen following a civil war.

\textbf{Collier and Hoeffler (Greed and Grievance in Civil War, 2004)}:
Model focuses around theory of the opportunity of rebellion. 
Civil wars more likely to occur after a previous civil war, effect decays over time. Per capita income has a negative, highly significant effect on the likelihood of the startup of a civil war. "An additional percentage point on the growth rate reduces the risk of war by about one percentage point" - I believe this is what Voth is referencing in footnote 8. Collier and Hoeffler also study the effects of a host of other variables on likelihood of war startup, though probably not relevant for us.

\subsubsection{Foreign wars}








One component of our study might be to check Voth theory of non destructing conflict until Napoleonian wars. Are conflict wealth destructing, and thus growth following a COllier and others evolution after conflict, or purely demographic shocks, positive on wealth growth?
Is the Malthusian argument a problem for our Proxy?

Also, we can, if we want, check reynal-querol democracy effect.

\subsection{Political institution and stability}

\textbf{Cox, North, and Weingast (The violence trap: a political economic approach to problems of development)}:
Regime defined ``as a state that exhibits leadership successions without violence. In other words, a regime ends when succession includes violence.'' Study 697 regimes in 162 countries since 1840, look at regime duration and its interaction with income.

\textbf{Alesina et al. (Political instability and economic growth, 1992)}:
Authors note that political instability hurts growth and low growth drives political instability. Also note that there may be shocks common to both growth and stability. Political uncertainty is not confined to violent regime change. Constitutional transfers of power can have similar effects. Authors find that growth is significantly lower in countries likely to experience a government collapse. Violent government changes are also associated with lower growth growth. They note that political instability is persistent.

\textbf{Jones and Olken (Do Leaders Matter? National Leadership and Growth Since World War II, 2005)}:
Studying leaders that succumbed to a natural or accidental death, found large, significant effects of leader quality on growth. This finding substantiates the claim that even constitutional transfers of power may have growth effects.

\textbf{Bodea and Elbadawi (Political violence and underdevelopment, 2008)}:
Focus on connection between political violence and economic development. Political violence leads to a ``general failure to create and implement a long-term development vision; and diminished legitimacy of the state.''

\textbf{Rodrik (Where did all the growth go? External shocks, social conflict, and growth collapses, 1998)}:
Argues that domestic social conflicts are a key way to understanding why growth rates lack persistence. Rodrik focuses on the effect of an external shock, though not necessarily violence or political upheaval. Proposes a model that the growth effect of an external shock depends primarily on the magnitude of the shock, the level of latent social conflict in the country, and the country's institutions of conflict management. Found that ``countries that experienced the sharpest drops in GPD growth after 1975 were those with divided societies and weak institutions of conflict management. The severity of external shocks is distinctly secondary.'' Rodrik also observed that once controlling for other variables, the government responses to shocks explained none of the growth changes.

\textbf{Olson (1993, 2000)} portrays dictators as rational wealth maximisers who have an incentive to become stationary rather than roving bandits because this will increase incentives of people to accumulate wealth which can be partially seized by the dictator. This is a theory of state formation.

\subsection{Length of regimes and stability}
\textbf{Alberto Alesina, Sule Ozler, Nouriel Roubini and Phillip Swagel, Political Instability and Economic Growth (Cambridge, Mass.: National Bureau of Economic Research, Working Paper No. 4173, 1992)}: 
They find that countries with a high incidence of government collapse have low economic growth, though they also find that low economic growth does not affect political instability.

\textbf{Feng, Yi. “Democracy, Political Stability and Economic Growth." British Journal of Political Science 27.3 (1997): 391–418}:
Feng’s finding supports Alesina et al.(1992) in the sense that regime change affects growth adversely. Mainly coups.

He defines a simultaneous equation system to measure instability:
where P1 = probability of irregular government change, P2 = probability of major regular government change, P3 = probability of minor regular government change. Models are estimated using one of the variables.

\textbf{Ari Aisen and Francisco Jose Veiga, “How Does Political Instability Affect Economic Growth? ” January 01, 2011 IMF Working Paper No. 11/12}:
They empirically examine the effects of political instability on economic growth. 
Using the system-GMM estimator for linear dynamic panel data models on a sample covering up to 169 countries, and 5-year periods from 1960 to 2004, we find that higher degrees of political instability are associated with lower growth rates of GDP per capita. 
Regarding the channels of transmission, we find that political instability adversely affects growth by lowering the rates of productivity growth and, to a smaller degree, physical and human capital accumulation. 

He constructed five alternative indexes of
political instability by applying principal components analysis. (It analyses the correlation matrix, and the variables are standardized to have mean zero and standard
deviation of 1 at the outset. Then, for each of the five groups of variables, the first component identified, the linear
combination with greater explanatory power, was used as the political instability inde)

Regime Instability Index 1: Cabinet Changes and Executive Changes.

Regime Instability Index 2: Cabinet Changes, Constitutional Changes, Coups,
Executive Changes, and Government Crises.

Regime Instability Index 3: Cabinet Changes, Constitutional Changes, Coups,
Executive Changes, Government Crises, Number of Legislative Elections, and
Fragmentation Index.

Violence Index: Assassinations, Coups, and Revolutions.

Political Instability Index: Assassinations, Cabinet Changes, Constitutional Changes,
Coups, and Revolutions.


\textbf{John B. Londregan and Keith T. Poole, 'Poverty, the Coup Trap, and the Seizure of Executive Power', World Politics, 32 (1990), 151-83.}:
They do not find evidence of reduced growth as a consequence of increased political instability; instead, they infer from their study that low economic growth increases the probability of political instability.

Instability are measured by using the probability of coups d'etat.

\textbf{Robert Barro, 'Economic Growth in a Cross-Section of Countries', Quarterly Journal of Economics, 106 (1991), 408-43}
They use single equation estimation to identify low economic growth as a result of political instability. 

They interpret "war" as influences on property rights and thereby on investment and growth. Results are shown that wars are significantly negative from growth.

\textbf{Darby, J, Li, CW \& Muscatelli, AV 2004, 'Political uncertainty, public expenditure and growth' European Journal of Political Economy, vol 20, no. 1, pp. 153-179}:
They argue that there is a significant link between increased political instability, reduced public investment and lower productivity growth in the OECD economies.
Using political data and a panel for various countries over the period 1960- 98, They show that there is a strong correlation between increased political instability and the reduction in government investment as a proportion of total fiscal spending.

Two indicators of instability: Using decade-average data for the ratio of government investment to total government spending and for the DCPG, GSE variables:

1. the number of changes in government complexion over the decade (DCPG)
based on the Woldendorp et al. CPG index

2. the percentage of seats held by the governing party or coalition averaged over each decade (GSE), which is an inverse measure of instability.

\textbf{Hossam Eldin Mohammed Abdelkader, Political Instability, Uncertainty, Democracy, and Economic Growth in Egypt, The Economic Research Forum 2015}:
They find that the impact of political instability on economic growth is ambiguous in the case of Egypt, while uncertainty level plays a significant role
The paper tests the uncertainty impact, resulting from unstable political and economic conditions on economic growth in Egypt. 
Accordingly, time-series data are used from 1972 to 2013 under the cointegration approach to determine the short- and long-run relationships. 
Moreover, a GARCH model approach is used in Error-Correction Model (ECM) to introduce the uncertainty impact, and Pesaran’s bound test is used to confirm the results.

Political instability are measured by:
Government Change(Cabinet changes), Revolution, Resignation of Executive, Assassination of Executive

Uncertainty are measured by:indirectly using the conditional variance of macroeconomic variables (i.e., GPD and inflation rate),), since political instability is affecting the economy through its impact on macroeconomic
measures. The conditional variance of GDP is estimated by a  (1,1) model.

\textbf{Overland, Simons and Spagat (Political Instability and Growth in Dictatorships,2005)} build a rational choice model of dictatorship and predict that a dictatorship, depending on initital conditions, will either lead to very high growth or deterioration of growth. They also predict that an autocrat in a very unstable regime is likely to plunder whereas only slightly unstable autocrats are likely to push for high growth (as opposed to Olson (1993) who predicts plundering for unstable autocrats in general).

\textbf{Sanhueza (The hazard rate of political regimes, 1997)}:
Hazard analysis of the relationship between regime duration and development. Author "found that economic development has a stabilizing effect in countries where democratic political institutions existed" (stabilizing with respect to regime duration). Did not observe an effect in countries with autocracies. Found that the occurrence of past failed coups actually improved regime survival for autocracies, but found no effect in democracies. Note: they refer to failed coups here, not all coups. Observed that while development did not affect stability of autocracies, the degree of popular discontent did reduce stability in autocracies. This result was much weaker in more democratic regimes. \textbf{Note:} Paper cites Sanhueza's phd dissertation which was unpublished and I could not find. He notes that the dissertation found that the "probability of a coup was inversely correlated to the duration of the political regime, suggesting that political regimes consolidate over time. He also found that autocratic regimes and democratic regimes differ in this respect."

\subsection{Economic and Political History}

\textbf{Acemoglu et al. (The Consequences of Radical Reform: The French Revolution, 2011)} look at the growth impact of French revolution. They note that before economic activity was dominated by an oligopoly consisting of  landed nobility and urban-based commercial groups which enjoyed superior legal status and blocked others’ entry. After the French conquered vast parts of the Holy Roman Empire by the end of the 18th century, they imposed their civil legal code which abolished feudal manor system and broke merchant and craft guilds. These reforms persisted only in some regions beyond the fall of Napoleon in 1815, mainly west of the Rhine river.

\textbf{Cantoni (Adopting a New Religion: The Case of Protestantism in the 16th Century Germany, 2012)} investigates the determinants of adoption and diffusion of Protestantism as a state religion. The paper notices a shift in sovereign power from the emperor to the princes in the 16th century which was accelerated by the emergence of Protestantism as it raised the question who has the authority to determine the religious affiliation of the empire. The conflict was settled in 1555 by granting territorial princes the right to determine the religious affiliation of their constituency. As nobody were allowed to impose their religious beliefs on their constituency anymore after the Peace of Westphalia in 1645 the princes’ choices had a very persistent effect on the religious affiliation of the territories they ruled then.

\textbf{Cantoni (The Economic Effects of the Protestant Reformation: Testing the Weber Hypothesis in the German Lands, 2014)} looks at whether the effect of Protestantism on economic growth as proposed by the Weber hypothesis holds. Channels through which Protestantism might have influenced economic growth are diverting labour and capital from the church, changing people’s attitudes in favour of new ideas and questioning hierarchies, trust-building amongst people benefitting market exchange and the accumulation of human capital through the promotion of literacy and elementary schools. It is noteworthy that free imperial cities unbound to territorial princes were quickest to adopt Protestantism.

\textbf{Cantoni and Yuchtman (Medieval Universities, Legal Institutions, and the Commercial Revolution, 2014)} study the role of the foundation of universities for expansion of economic activity in Germany. Whereas the first university was founded in Bologna in the 11th century, a sharp rise in the number of people attending universities happened as the first universities were founded in Germany during the Papal Schism in 1386. The hypothesised channel from universities to economic growth is via the training of legal and administrative experts who then developed institutions reducing the uncertainty of market exchange. Their proxy for economic activity is the granting of market rights.

\textbf{Volckart (State Building by Bargaining for Monopoly Rents, 2000)} proposes a theory of state formation saying that the origin of state formation in Central Europe was contractual, based on mutually advantageous agreements between organised interest groups, in particular military security providers and commercial cartels (merchant and craft guilds). The main hypothesis is that the reduction in transaction costs in the market of security was a necessary condition for the monopolisation process leading to state formation which was further supported by the monetarization of the economy and the transformation of security from a private into a public good. The paper then discusses why the Holy Roman Empire as a whole failed to monopolise security provision and legal enforcement via coercion but some of its vassal states such as Prussia and Württemberg succeeded in it for their respective territories.
\fi

\section{Literature Review}

\subsection{Political Stability and Economic Growth}

In order to consider theoretical arguments and empirical evidence on the interaction of regime length and economic growth and development, we focus on the literature that studies this relationship in the context of an autocratic regime. It fits well with our context, since in terms of legal, political and economic power, the Holy Roman Empire was characterized by a huge gap between the aristocracy and church on the one hand and the commoners on the other hand. 

Olson (1993, 2000) proposes that in a state of anarchy groups specialized in violence (roving bandits) have an incentive to permanently protect a specific group of people because otherwise, always expecting roving bandits to plunder their possessions, nobody would want to accumulate any sort of wealth. Thus roving bandits become stationary bandits and provide the basic public good of security and law enforcement, which incentives the protected group of people to accumulate wealth and supply labor, in exchange for some of the proceeds of the emerging economic activity.

In the same line, identifying the occurrence and threat of violence as the root obstacle to development, Cox et al. (2013) say that “complex specialized economies capable of providing sustained growth cannot be established without reformed states and reformed states cannot be created without complex specialized economies”. 

Volckart (2000) proposes the hypothesis that the Holy Roman Empire was formed after the 14th century as a result of a reduction in transaction costs such that groups holding military and economic power started to bargain which led to a more monopolized provision of security and law enforcement by coercion. He further points out that the empire as a whole never succeeded in establishing such a monopoly but some territories such as Prussia and Wuerttemberg did while others did not, that is, there was regional variation with respect to the stability of regimes in territories of the empire.

Focusing on the dictatorships and looking at the potential link between stability and growth, the literature offers us strong insights on the expected relation.
Overland et al. (2005) predict that dictatorial political systems experience a high cross-regime variance of growth outcomes as dictatorships lead either to very high or very low growth. \footnote{ Their prediction is based on a rational choice model of dictatorship.}  

Wintrobe (1990) proposes a theory of dictatorship that distinguishes between ideological, totalitarian dictators and pure wealth-maximising dictators. It assumes that political power is a function of repression and loyalty of a dictator’s constituents and that totalitarian dictators maximise power itself whereas wealth-maximising dictators only produce power up to the minimum necessary in order to remain in office and be able to extract wealth. The model predicts an increase in loyalty and decrease of repression in the composition of a wealth-maximising dictator if economic growth occurs (and vice versa if economic contraction occurs). For totalitarian dictators, it predicts that political power itself will increase as a result of economic growth. Thus, the paper suggests that economic growth increases the stability of political regimes.

Studying the main direction of the effect, even though disagreeing on the level of instability, both Olson (1993) and Overland et al. (2005) predict that autocratic rulers in very unstable political regimes are more likely to plunder the economy. This implies a strong negative impact of instability on growth. 

Looking at the opposite causality, Sanhueza (1997) finds no effect of economic development on the stability of autocratic regimes but stresses the importance of popular discontent as a driver of political stability.\footnote{However, many other papers do view political stability as endogenous to economic growth, making it very hard to identify a direction of causality.}

Following the same notion of popular discontent, Alesina et al. (1992) argue that not only violent regime changes but also constitutional transfers of power constitute a source of political uncertainty that harms economic growth. They further note that political instability tends to be persistent. 

\subsection{Wars}

From the above literature, linking political stability with violence, we then turn to the direct impact of civil wars on growth.  Due to data availability, the majority of growth literature concerned with the effects of violence is confined to 20th century violent episodes. 

Many authors find that 20th century violence is associated with significant growth reductions (Collier 1999, Alesina et al. 1992, Bodea and Elbadawi 2008, Murdoch and Sandler 2004), though Londregan and Poole (1990) find no systematic effect of coups on income growth. They suggest this is the result of averaging over a bi-modal population; the coup effect is ambiguous and depends on whether the coup faction has pro-growth policies or policies that retard growth. Moreover, some regime changes may be viewed positively by economic agents, and some negatively (Alesina et al., 1992).

Ultimately the key consequences of civil wars are destruction of resources, social disruption, and diversion of public expenditure toward the military and away from output-enhancing activities (Collier, 1999). 

Some authors find that the indirect growth effects of civil wars, particularly through uncertainty and the disruption of economic activity, outweigh the direct costs (Murdoch and Sandler 2004, Bodea and Elbadawi 2008, Hoeffler and Reynal-Querol 2003). 

Hoeffler and Reynal-Querol (2003) argue that the main problem of civil war tends to be the post-war severe public health consequences. Collier (1999) and other authors also cite the importance of capital flight. We note that the predominantly agricultural economies of the middle ages had little reliance on human capital, and due to the lack of modern transportation and developed financial markets, physical and financial capital flight were likely too small to impact growth.

But the direction of causality is unclear. Londregan and Poole (1990) and Collier and Hoeffler (2004) observed that coups and civil wars, respectively, are more likely when growth rates are low. Estimating the joint determination of political instability and growth, Alesina et al. (1990) found no effect of growth on the propensity of government change.

\subsubsection{Regime and government changes}

Turning to regime changes, the rich literature focusing on it finds overall a negative correlation with growth; in line with Sanhueza (1997) and Alesina et al. (1992).
We use Cox, North, and Weingast (2013) definition of a regime ``as a state that exhibits leadership successions without violence. In other words, a regime ends when succession includes violence.''  However, regime changes show specificities compared to violent episodes in general, for they imply political violence. 

Bodea and Elbadawi (2008) find a negative connection between political violence and economic development. Through regime changes, it leads to a ``general failure to create and implement a long-term development vision; and diminished legitimacy of the state.'' 
This negative effect is enhanced via a vicious circle described by Alesina et al. (1992). They note that the reduced growth induced by political instability will then have a negative impact on stability. In their paper, they emphasize this result for shocks common to both growth and stability, thus self-supporting. It implies a persistence of political instability.

On top of this main effect, Rodrik (1998) shows that other things being equal, the level of latent social conflict in the country are more sensitive to exogenous negative shocks on wealth. A country subject to violent change will thus be more vulnerable to such a shock.

Another side of the literature focuses on potential positive effects of regime changes on growth, mainly through the change of quality of institutions and leaders.

On the specific case of the French revolution (definitely a regime change), Acemoglu et al. (2011) note that the introduction of a new civil code had a positive effect on the quality of institutions.

Londregan and Poole (1990) show that the very nature of the regime changes will have different consequences. Revolutions often cause a significant reorganization of society while coups tend to maintain the existing power structure.

More generally, Jones and Olken (2005) support the idea that a change for a better leader, even though it is violent, has a positive impact on growth.

Jones and Olken (2005), in line with Alesina et al. (1992) support the idea that political uncertainty is not confined to violent regime changes. Government changes, like constitutional transfers of power, can have similar effect. \footnote{In their paper, they observe the impact of natural death of leaders compared to accidental.}

In parallel with regime changes, several opposite effects of government changes are observed.

Supporting the idea of ambiguous effects, Hossam Eldin Mohammed Abdelkader (2015) find that the impact of political instability on economic growth can go in opposite directions in the case of Egypt. However they find that the wider notion of uncertainty level (considering other uncertainty proxies) plays a significant role.

Londregan and Poole (1990) find the identical results for regime and government changes, namely that effects can go in both direction, depending on if the viewed favorably by economic agents,\footnote{The uncertainty effect of political instability is lessened.} 
But overall, uncertainty about the policies of a new government hurts productive economic decisions, locally and through foreign investors.

Their results are valid whatever the nature of government change.\footnote{They compare smooth transition to the ones that involve ideological turnover or change in the nature of regime.}

.


\section{Econometric Model}
Panel data model for intervals is used to estimate the impact of regime changes and wars on economic growth, which takes the general form of (1), where $y_{it}$ is economic growth for city $i$ at time $t$ proxied by construction of notable buildings, market creation, population and economic activity, $X_{it}$ is a vector of regime duration, change and type dummy variables and $Z_{it}$ is a vector of wars duratin, types and identity variables in the city, $W_{it}$ is a vector of control variables including percentage of clerical construction, religion, geography, human capital, instiution, city types and regime size. $\beta$ and $\gamma$ are vectors of coefficients to be estimated in order to determine the relationship between economic growth and regime changes, and between economic growth and wars, respectively. $\delta$ are vectors of coefficients to be estimated for the control variables. Also, $\epsilon_{it}$ is the error term of the estimated model.

\begin{equation}
y_{it} = \alpha + \beta X_{it} + \gamma Z_{it} + \delta W_{it}+ \epsilon_{it}
\end{equation}

\subsection{Main Regression (900 -1815)}
A Fixed Effects Model is used here to estimate as our main regression from 900 to 1815, as the following:

\begin{equation}
\Delta y_{it} = \alpha * wars_{it} + \beta * changes_{it} + \gamma * length_{it} + \delta * W_{it}+ f_{i}i + \epsilon_{it}
\end{equation}
Where $y_{it}$ is the number of construction in city $i$ in internal $t$, $wars_{it}$ is the years of war in city $i$ in internal $t$, $length_{it}$ is number of regime changes in city $i$ in internal $t$, $W_{it}$ are the city-level control variable (religion, geography, type of regime, type of change, type of construction, type of war etc.) in city $i$ in internal $t$. To be specific, $\alpha$, $\beta$ and $\gamma$ are coefficients to be estimated in order to determine the relationship between economic growth and wars, between economic growth and regime changes, and between economics growth and regime lengths. $\delta$ are coefficients to be estimated for the control variables. Moreover, standard errors will be clustered on a region level.


\subsection{Main Regression (1800-1900)}
Cross-Section Regression for long-run growth post-1800 is to be estimated, which takes the form of (3), Where $y_{rs}$ is is economic growth proxied by urbanisation rate in region $r$ (ca. 20) at year $s$, $wars_{r}$ is average total war years of cities in region $r$ . $changes_{r}$ is average number of regime changes in region $r$ , $length_{r}$ is average of longest regime of cities in region $r$ , $W_{rs}$ are region-level control variables (religion, geography, type of regime, type of change, type of war, institutions etc.),  $\alpha$, $\beta$ $\gamma$ are coefficients to be estimated in order to determine the relationship between economic growth and wars,  between economic growth and regime changes, and between economics growth and regime length. $\delta$ are coefficients to be estimated for the control variables.

\begin{equation}
\Delta y_{rt} = \alpha * wars_{r} + \beta * changes_{r} + \gamma * length_{r} + \delta * W_{rs}+ \epsilon_{r}
\end{equation}

\subsection{Robustness Checks (900-1815)}
We perform robustness checks in model (2) and (3).  In Model (2), $y_{it}$ would be measured by population data instead of construction
and $wars_{it}$ would be measured by number of years instead of war years, respectively. In Model (3), $y_{ds}$ would be measured by industrialization rate in districts d (ca. 60) in 1849-1900, $wars_{r}$ would be measured by we use number of years instead of war years. Also, different weights would be considered to construct regional averages of data. 

\subsection{Predictions}
For standard predictions of our model (2) and (3). Negative coefficients are expected on $changes_{it}$  and $change_{r}$ while
positive coefficients are expected on $length_{it}$  and $length_{r}$. Also, these effects are also expected to slowly die out in model (3). For Non-Standard Predictions, 
coefficients of $wars_{it}$ and $wars_{r}$ could be positive,
coefficients would become negative with more robust control, napoleonic influence by Acemoglu et al. (2011)
foreign vs. civil wars: Voigtländer, Voth (2012) 

\section{Data Description}


\section{Results}
\pagebreak


\begin{figure}
\begin{singlespace}{
\scalebox{0.8}{
\def\sym#1{\ifmmode^{#1}\else\(^{#1}\)\fi}
\begin{tabular}{l*{1}{c}{c}{c}{c}{c}}
\multicolumn{6}{l}{\hfil\textbf{Table 1: Construction Activity: from 900 to 1800}}\\
        Regression variables&&&&&\\
        &(1)&(2)&(3)&(4)&(5)\\
\hline
Regime changes	&0.0373	    &0.0181   	&       	&	&0.0347	\\
            	&(0.82)	    &(0.51)   	&	        &	&(0.66)	\\
Longest regime	&-0.000137	&	        &0.00116**	&          	&0.00145**	\\
            	&(-0.45)	&          	&(3.74)    	&       	&(3.80)	\\
Years of wars	&-0.000763	&       	&       	&0.00590	        &0.00210	\\
            	&(-0.21)	&       	&       	&(0.92) 	        &(0.39)	\\
cons        	&-1.021	    &1.027***	&0.783***	&1.146***	&0.882***	\\
            	&(-1.94)	&(105.49)	&(11.80)	&(143.13)	&(9.62)	\\
Nunber of observations	&8108	&13816	&13816	&9045	&8108	\\
Number of cities&1693	&1693	&947	&929	&929	\\
\hline
\hline
\multicolumn{6}{l}{\footnotesize \textit{t} statistics in parentheses}\\
\multicolumn{6}{l}{\footnotesize \sym{*} \(p<0.05\), \sym{**} \(p<0.01\), \sym{***} \(p<0.001\)}\\
\multicolumn{6}{l}{\footnotesize All regressions were run with city-level fixed effects and standard errors clustered on the 22 regional levels}\\
\multicolumn{6}{l}{\footnotesize Column 1 includes time dummies (not reported)}\\
\end{tabular}
}}
\end{singlespace}
\end{figure}



\begin{figure}
\begin{singlespace}{
\scalebox{0.8}{
\def\sym#1{\ifmmode^{#1}\else\(^{#1}\)\fi}
\begin{tabular}{l*{1}{c}{c}{c}{c}{c}}
\multicolumn{6}{l}{\hfil\textbf{Table 2: Construction Activity: from 900 to 1800}}\\
        Regression variables&(6)&(7)&(8)New Constructions&(9)First &(10) First Difference\\
        &&&&Difference&of new construction\\
\hline
Regime changes	&0.0348	&0.0425	&0.0394	&-0.0157	&-0.0374	\\
	&(0.77)	&(0.69)	&(0.85)	&(-0.33)	&(-0.83)	\\
Longest regime	&-0.000135	&-0.000138	&-0.000185	&0.000218	&0.000159	\\
	&(-0.44)	&(-0.46)	&(-0.77)	&(0.96)	&(1.27)	\\
Years of wars	&-0.000249	&-0.000727	&-0.00583	&0.00435	&-0.00241	\\
	&(-0.06)	&(-0.18)	&(-1.66)	&(0.75)	&(-0.49)	\\
Lag of years of war	&0.0108	&0.0108	&0.00616	&0.0107	&0.0126**	\\
	&(1.45)	&(1.44)	&(0.96)	&(1.95)	&(2.96)	\\
Percentage 	&	&0.00497	&0.0264	&-0.168	&-0.0782	\\
of expensive wars	&	&(0.04)	&(0.30)	&(-0.77)	&(-0.54)	\\
Percentage &	&0.0421	&0.00329	&-0.226	&-0.177	\\
of destructive wars	&	&(0.34)	&(0.03)	&(-1.47)	&(-1.47)	\\
Years of occupation	&	&-0.000579	&-0.00146	&-0.0251*	&-0.0196	\\
	&	&(-0.03)	&(-0.10)	&(-2.36)	&(-1.36)	\\
Number of regime 	&	&-0.0786	&-0.0324	&0.0519	&0.139	\\
changes through conflict	&	&(-0.54)	&(-0.32)	&(0.49)	&(1.54)	\\
Years of conflicts 	&	&-0.00390	&0.00144	&0.00939	&0.00420	\\
over inheritance	&	&(-1.48)	&(0.50)	&(1.20)	&(0.73)	\\
Years of conflicting claims	&	&0.0122	&0.00651	&0.00917	&0.00911	\\
	&	&(1.18)	&(0.88)	&(1.33)	&(1.51)	\\
cons	&-1.020	&-1.020	&-0.545	&-0.302*	&-0.278*	\\
	&(-1.95)	&(-1.94)	&(-1.61)	&(-2.62)	&(-2.58)	\\
Number of cities 	&8108	&8108	&8108	&7445	&7445	\\
Number of city groups&929	&929	&929	&907	&907	\\

	\hline
	\hline
\multicolumn{6}{l}{\footnotesize \textit{t} statistics in parentheses}\\
\multicolumn{6}{l}{\footnotesize \sym{*} \(p<0.05\), \sym{**} \(p<0.01\), \sym{***} \(p<0.001\)}\\
\multicolumn{6}{l}{\footnotesize All regressions were run with city-level fixed effects and standard errors clustered on the 22 regional levels}\\
\multicolumn{6}{l}{\footnotesize All regressions are run including time dummies}\\
\end{tabular}
}}
\end{singlespace}
\end{figure}



\begin{figure}
\begin{singlespace}{
\scalebox{0.8}{
\def\sym#1{\ifmmode^{#1}\else\(^{#1}\)\fi}
\begin{tabular}{l*{1}{c}{c}{c}{c}{c}{c}}
\multicolumn{7}{l}{\hfil\textbf{Table 3: Growth rate of population: from 1650 to 1850}}\\
        Regression variables&(1)&(2)&(3)&(4) &(5) &(6)\\
\hline
Lag of regime changes	&-0.00806	&	        &	&-0.0537	&-0.0349     &-0.00409	\\
                    	&(-0.33)	&       	&    &(-2.08)	&(-1.17)	&(-0.11)	\\
Lag of longest regime	&       	&0.000275	&           &0.000332	&0.0000356	&0.0000724	\\
                    	&       	&(1.15)  	&	        &(0.90)	    &(0.15)	    &(0.29)	\\
Lag of years of war	&           	&	        &0.000527       	&0.00233	&0.00142	&-0.00148	\\
                    	&       	&	        & (0.10)	      	&(0.34)	    &(0.24)	    &(-0.28)	\\
Lag of percentage 	&	&	&	&	&0	&-0.0542	\\
of expensive wars                                	&	&	&	&	&(.)	&(-0.94)	\\
Lag of percentage	&	&	&	&	&0.0656	&-0.0214	\\
 of destructive wars	&	&	&	&	&(1.11)	&(-0.44)	\\
Lag of years of occupation	&	&	&	&	&	&-0.00629	\\
	&	&	&	&	&	&(-0.26)	\\
Lag of number of regime 	&	&	&	&	&	&-0.0990	\\
changes through conflict	&	&	&	&	&	&(-1.29)	\\
Lag of years of conflicts 	&	&	&	&	&	&0.0360**	\\
over inheritance	&	&	&	&	&	&(3.33)	\\
Lag of years	&	&	&	&	&	&-0.00416	\\
 of conflicting claims	&	&	&	&	&	&(-1.27)	\\
cons	&0.754***	&0.669***	&0.752***	&0.666***	&0.719***	&0.727***	\\
    	&(101.58)	&(9.53)	    &(95.75)	&(6.37)	&(10.45)	&(9.17)	\\
N	&578	&575	&405	&377	&367	&367	\\
\hline
\hline
\multicolumn{7}{l}{\footnotesize \textit{t} statistics in parentheses}\\
\multicolumn{7}{l}{\footnotesize \sym{*} \(p<0.05\), \sym{**} \(p<0.01\), \sym{***} \(p<0.001\)}\\
\multicolumn{7}{l}{\footnotesize These regressions were run using regional dummies}\\
\end{tabular}
}}
\end{singlespace}
\end{figure}




\begin{figure}
\begin{singlespace}{
\scalebox{0.8}{
\def\sym#1{\ifmmode^{#1}\else\(^{#1}\)\fi}
\begin{tabular}{l*{1}{c}{c}}
\multicolumn{3}{l}{\hfil\textbf{Table 4: Cross Section: Year of Market Foundation}}\\
        &(1)&(2)\\
        \hline
Longest regime	&-0.0959*	&-0.0928**	\\
	&(-2.16)	&(-2.90)	\\
Total years of wars	&0.0340	&	\\
	&(0.08)	&	\\
Percentage 	&21.31	&	\\
of expensive wars	&(0.90)	&	\\
Percentage 	&15.49	&	\\
of destructive wars	&(0.69)	&	\\
Latitude	&25.67***	&37.88**	\\
	&(4.90)	&(2.83)	\\
Longitude	&4.412	&-3.649	\\
	&(1.43)	&(-0.47)	\\
Year of foundation	&0.301***	&0.348***	\\
	&(7.76)	&(12.32)	\\
cons	&-300.9	&-901.2	\\
	&(-1.14)	&(-1.22)	\\
N	&393	&730	\\
\hline
\hline
\multicolumn{3}{l}{\footnotesize \textit{t} statistics in parentheses}\\
\multicolumn{3}{l}{\footnotesize \sym{*} \(p<0.05\), \sym{**} \(p<0.01\), \sym{***} \(p<0.001\)}\\
\multicolumn{3}{l}{\footnotesize These regressions were run using regional dummies}\\
\end{tabular}
}}
\end{singlespace}
\end{figure}


\pagebreak




\section{Discussion}

\section{Conclusion}

\bibliographystyle{plain}
\nocite{*}
\bibliography{Cities}


\end{document}







