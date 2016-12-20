# CMS/Events Tasks

- [Template Implementation](#template-implementation)
- [Content from Past Events](#content-from-past-events)
- [Random Housekeeping](#random-housekeeping)

## Template Implementation

1. Need named options for event categories and Gym course types
    - i.e. background color for event banner
        - maybe as a conditional class based on front-matter event category parameter?
1. Extract forms into include files with frontmatter parameters
1. Need content for at least one past event
1. Placeholder video player

## Content from Past Events

- **Panelist Photos**
    - Color: standardize with b/w?
    - Format: rectangle and/or square?
    - Size: current design uses 180px (h) x 160px (w)
- **Event Details**
    - Short description
    - Call-outs
    - OG share images
    - OG meta descriptors
    - Video ID
- **Panelist Bios**
    - e.g. for `/_includes/bios/emarcotte.html`:

```
<section class="event-bio">
  <img alt="Ethan Marcotte" src="{{ page.baseurl }}/cms/img/bio-ethan-marcotte.jpg">
  <h2>Ethan Marcotte</h2>
  <p>Ethan, perhaps best known for coining the term “responsive web design”,  is an author, speaker, and web designer who is passionate about beautiful design, elegant code, and the intersection of the two. Over the years, his clientele have included <cite>People Magazine</cite>, <cite>New York Magazine</cite>, the Sundance Film Festival, and <cite>The Boston Globe</cite>. Ethan’s acclaimed books, <cite>Responsive Web Design</cite> and <cite>Responsive Design&colon; Patterns and Principles</cite>, show how designers and organizations can leverage the web’s flexibility to design across mobile, tablet, and desktop—and whatever might come next.</p>
</section>
```

## Random Housekeeping

1. Take down old blog (republish any on medium)
1. Solve favicon mess
1. 404 page
