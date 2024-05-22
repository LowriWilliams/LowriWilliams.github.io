<!-- ---
cms_exclude: true

# To publish author profile pages, remove all of the `_build` and `cascade` settings below.
_build:
  render: never
cascade:
  _build:
    render: never
    list: always
--- -->

---
title: Meet the Team
type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Principal Investigators
        - Researchers
        - Grad Students
        - Administration
        - Visitors
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true
---