# AICrossSim Website

This guide explains how to add team members and research projects to our website via pull requests.

## Table of Contents
- [Adding Team Members](#adding-team-members)
- [Adding Research Projects](#adding-research-projects)
- [Submission Process](#submission-process)

## Adding Team Members

1. Edit `_data/team.yml`.
2. Add your entry under the appropriate section (faculty, phd_students, or ras).
3. Include a profile image in `assets/images/team/` (Refer to [This Commit](https://github.com/AICrossSim/aicrosssim.github.io/commit/8c9922ca54da3b3a5dc0712e3b33c4e6949d3c26) for an example).

### Team Member Template

```yml
# Template for new entries (copy and modify):
  - name: "Full Name"
    role: "Research Area/Topic" # Keep it short, in a few words
    image: "/assets/images/team/your-image.jpg"  
    personal_url: "https://your.website"         # Could be any personal profile 
```

## Adding Research Projects

1. Create a new file in `_projects/`.
2. Include a cover image in `assets/images/research/` (Refer to [This Commit](https://github.com/AICrossSim/aicrosssim.github.io/commit/b70d6aa02202b4062ff55d6142168a419b403ae9
) for an example).