# ICT-Index
## Keyword Search for Transcribed ICT Video Content

### Github Search Syntax Reference
- Official Docs
    - https://docs.github.com/en/search-github/getting-started-with-searching-on-github/about-searching-on-github

- Cheat Sheet Gist
    - https://gist.github.com/bonniss/4f0de4f599708c5268134225dda003e0

### Notes
- The file naming convention is videoId_transcription.json
- The video id can be used for reference if needed.
- There is a 1:1 relationship between video and transcription file.

### Use Case
- Keyword Search
- Use Github's Search and Limit Search Scope to This Repo

    ![Keyword Search](./readme-resources/KeywordSearchExample.jpg) 

- Search for Keywords with Github's search syntax.
- "Fair Value Gap" will find the full term (Fair Value Gap)
- Fair Value Gap will find all files with Fair OR Value OR Gap

- Search results provide a generated url with a time offset, to the point when the term is used in the video.

    ![SearchResults](./readme-resources/SearchResults.jpg) 
    
- Select the URL of interest from the search results
    - `https://www.youtube.com/watch?v=FgacYSN9QEo&t=33`
    
    ![SelectURL](./readme-resources/CopyVideoURL.jpg)

- Review the content of interest
    
    ![SelectURL](./readme-resources/ReferenceVideoOffset.jpg)
