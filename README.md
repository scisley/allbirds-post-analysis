# Overview
This repo contains the raw data, manual coding, and full output for an analysis performed by Steve Isley in August of 2022. 

I'm analyzing [this feed](https://www.linkedin.com/feed/update/urn:li:activity:6962747441062281216/).

Performed on August 15th, 2022 at 7:08pm PT. Comments added after this were ignored. At that time, there were 1,248 comments, 928 shares, and 27,365 reactions. I left the ranking as the default "Most Relevant" and then clicked the "see more" button until it stopped letting me see more. Then I opened my dev console, found the parent DIV, and copied all the outer HTML (Chrome browser). This resulted in about 190k lines of text.

It only let me pull 1,038 comments (though this might be all of them since the total comment count includes comment-replies and my data scrape only pulled in one reply)

200 comments (split between top level comments and replies) are truncated with a "...see more" notice.

# Instructions

Download the full contents of the repository, then view the allbirds-post-analysis.html for the final results (complete with R code)
