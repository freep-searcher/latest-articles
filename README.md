# frontpage
## What is this?

This repo contains a snapshot of data captured from the freerepublic.com forums.
The data is captured as a timeseries. You can explore the dataset by using
the `latest-articles.ipynb` file, or accessing the data directly in the
`data/latest-articles.csv` file.

Other sidebars displayed on the forum, like "Breaking News", are not included
in the dataset.

In the spirit of quarterly freepathons the data will be rolled over each
quarter and tagged. If you want previous quarter's data check for the relevant
tag. Unfortunately there is no historic data going back over the site's
multi-decade long history, only data as recent as 2021.

## Why?

Discussion on this site is often facilitated by sharing links from other
websites. These are defined as `sources` in the Jupyter notebook. Unsourced
posts, or vanity posts in the freeper parlance, are categorized apart from
sourced posts.
The dataset contains information about when a particular link was listed in the
"Latest Articles" portion of the page, who posted it, what time it was posted,
and how many replies the article accumulated before it is aged out.

## Contributing

1. `git clone` this repo.
1. Modify the Jupyter notebook.
1. Send a pull request.
