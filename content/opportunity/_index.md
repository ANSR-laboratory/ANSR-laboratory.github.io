---
# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: 'opportunity.png'

sections:
  - block: collection
    id: posts
    content:
      title: Join Us!
      subtitle: ''
      text: |
        You can browse our list of open positions (if any) here, as well as get an insight on the type of positions we typically advertise by browsing through our list of previous openings. We are also supportive of hosting strong PhD candidates and researchers supported by a personal fellowship/grant.
        
        **Please note:** applications for the listed positions need to be made through the Mass General Brigham (MGB) portal to be formally taken into acount.
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - opportunity
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: showcase
      # Choose single or dual column layout
      columns: '1'
---