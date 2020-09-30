## Projects

### versusverses

versusverses generates minimalist mash-ups of two or more poets, using markov chains.

> In twenty years I was fresh and cheerful, who but I?
>
> Rushes in a net deliberately cast over the terrible pain,  
> I loved you for life, but life has quite gone by.  
>
> -- _Christina Rossetti versus Sylvia Plath versus Louise Glück_

A random selection of poets and their body of work is fed into the [markovify](https://github.com/jsvine/markovify) combine harvester, with each corpus' contribution to the mix weighted according to relative size. Currently, the program is configured for a 1-line/2-lines/2-lines/1-line stanza scheme, with the first and last lines acting as a refrain.  

> Death had the Mercy, you're done with the smut and smog and smoke of our nights:  
> 
> They charmed it with care;  
> You and I see the shadows falling,
> 
> It got up that afternoon--walked to the vibration thru the grocerystore,  
> Thou art slave to fate, chance, kings, and none but fair,
> 
> Death had the Mercy, you're done with the smut and smog and smoke of our nights.  
>
> -- _Allen Ginsberg versus Lewis Carroll versus John Donne versus Anna Akhmatova_

#### Assembly line:

1. Poetry corpora, scraped from [PoemHunter](https://www.poemhunter.com/)'s Top 500 Poets. 
2. Code to read and markovify each corpus and generate new poems. 
3. TODO: A Twitter account for publishing the poems. 
4. TODO: A Heroku account for deployment and automation. 
5. GOAL: The bot runs unsupervised, drunk on its freedom. 
