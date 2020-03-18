# US-COVID-SIR
An SIR model of U.S. Covid-19 progression 

## Explanation of the symbols
$S$ for the number of **s**usceptible, $I$ for the number of **i**nfectious, and $R$ for the number **r**ecovered (or immune) individuals. 

Between $S$ and $I$, the transition rate is $\beta$. The average number of contacts per person times the probability of disease transmission in a contact between a susceptible and an infectious subject.

Between $I$ and $R$, the transition rate is $\gamma$. The rate of recovery or death - 'removal rate'. Here we simply assume that the birth rate(health babies) equals the death rate. i.e. the total population in an area remains.) If the duration of the infection is denoted $T_g$, then $\gamma = 1/T_g$, since an individual experiences one recovery in $T_g$ days.

Transition rates have unit of $\dfrac 1 {day}$

<object data="http://yoursite.com/the.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="http://yoursite.com/the.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="http://yoursite.com/the.pdf">Download PDF</a>.</p>
    </embed>
</object>
