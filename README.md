## Nandar Min Tun, M.A.(International Development)
### School of International Service, American University

I do things with data. Data is *so* fun.

I love climbing.

I am planning to learn Arabic. 


### Skillz
- Programming
  - `R/RStudio` especially `tidyverse` like `ggplot(data = x, aes(y=var1))`
  - Java
  - html
  - C++
  
- Statistics and econometrics
  - Descriptive analysis
  
 ### An example of my skill
 Here is some code I wrote in `R`:
 
 ```
 #codebook table
 
 cbfactor=function(.data, x) {
  x=enquo(x)
  count(.data, x) %>%
    mutate(
      values= as.numeric (x),
      labels=as_factor(x),
      freq=n,
      perc=n/sum(n)*100,
      .keep= 'unused'
    ) %>%
    knitr::kable(format='pipe', digits=1L)
}
```
~~~

Now test it out
~~~
```
cbfactor=function(.data, x) {
  x=enquo(x)
  count(.data, x) %>%
    mutate(
      values= as.numeric (x),
      labels=as_factor(x),
      freq=n,
      perc=n/sum(n)*100,
      .keep= 'unused'
    ) %>%
    knitr::kable(format='pipe', digits=1L)
}
```
  
### Hi there 👋

<!--
**nandarmintun/nandarmintun** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on finishing my Masters in International Development.
- 🌱 I’m currently learning R and Arabic.
- 👯 I’m looking to collaborate on R projects.
- 🤔 I’m looking for help with R.
- 💬 Ask me about Myanmar/Burma.
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
