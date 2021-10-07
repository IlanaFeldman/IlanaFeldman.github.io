2021-10-7-ST558-Project1-Blog
================
Ilana Feldman
10/7/2021

## Project 1 Report

The requirements of my project were to connect to an API using functions
capable of connecting to at least six endpoints and to use them to
gather data and perform a statistical analysis. I used PokéAPI for this
project. Although I don’t know very much about Pokémon, having never
played it or watched the show, I have worked with item sets in unrelated
environments in the past that could provide boosts under specific
conditions, and the existence of berries caught my interest, so I
decided to pull up endpoints related to them to find any interesting
connections.

I was surprised by the variety of berry sizes. Some were only 20mm,
which, assuming that’s a diameter, feels about average compared to a
blueberry or similar real-life fruit, but others were over 10 times that
diameter. While some larger fruits such as bananas are botanically
considered to be berries, I was still caught off-guard by the fact that
such a size difference existed in the Pokémon universe. This seems to be
fairly consistent across all types of berries when you sort them by item
categories, other than those that are designated as “medicine”, which
are closer to the expected blueberry size. Some of the large berries
were even flingable, although the vast majority of berries that could be
flung were much smaller. I also noticed that berries of the same item
category usually had similar statistics when it came to smoothness and
natural gift power, and that the growth time and soil dryness of each
berry seemed to have a relationship that was very strictly defined and
almost logarithmic. Perhaps the most surprising result, however, was
that there didn’t seem to be much of a relationship between the growth
time and the size. This felt like it would be the easiest way to
organize such items. Another possibility was that berries with higher
natural gift power took longer to grow, and this does seem to be the
case for berries with the highest natural gift power, but this is a
factor variable with only three levels, and the first two levels appear
to be about the same. There didn’t seem to be any data on the API about
the rarity of each berry, so my best guess would be that berries are
“balanced” by the need to have the right kinds for each type of
pokémon that you control.

Easily the most difficult part of the project was just getting started.
There was very little information about how to actually construct an API
in the class, and I find that searching for things on the web is a lot
less effective unless I’m very specific about what I’m looking for, such
as a specific command. I ended up relying on the source that was linked
in the lecture and occasional helpful tips from my classmates. I was
also not sure on how to properly split a list, and dataframes within
those lists, without going extremely far out of my way to cater to the
specific layout of those lists. There were a lot of errors related to
the row counts being different from each other and/or 1, and I tried to
keep my code as similar as possible from endpoint to endpoint, but for
most of them I inevitably changed a few things out. I think my biggest
issue, though, was that I didn’t start until this previous weekend. With
more time to explore exactly how the output of fromJSON was structured
and to find solutions, I feel like I could have come up with a more
elegant way to read in the information from APIs.
