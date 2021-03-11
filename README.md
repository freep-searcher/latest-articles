# The Latest Articles
## What is this?

This repo contains a snapshot of data captured from the freerepublic.com forums.
The data is captured as a timeseries. You can explore the dataset by using
the `latest-articles.ipynb` file, or accessing the data directly in the
`data/latest-articles.csv` file.

Other sidebars displayed on the forum, like "Breaking News", are not included
in the dataset.

In the spirit of quarterly freepathons the data will be rolled over each
quarter, tagged, and the csv file overwritten with the new quarter's incoming
data. If you want previous quarter's data check for the relevant tag.
Unfortunately there is no historic data going back over the site's
multi-decade history, we only have data as recent as 2021.

## Why?

Discussion on this site is often facilitated by sharing links from other
websites. These are defined as `sourced` in the Jupyter notebook. Unsourced
posts, or `vanity` posts in the freeper parlance, are categorized apart from
sourced posts.

The dataset contains information about when a particular link was listed in the
"Latest Articles" portion of the page, who posted it, what time it was posted,
and how many replies the article accumulated before it is aged out.

With this information we can build an understanding of topics like which
posters facilitate the most discussion and where they are sourcing their
information from.

## Contributing

If you are a practiced data scientist and can perform a deeper analysis than
what is already here we would love to see what you can do with this data!

1. `git clone` this repo.
1. Modify the Jupyter notebook or create your own.
1. Update this readme with new information about your changes if it's relevant.
1. Send a pull request.
