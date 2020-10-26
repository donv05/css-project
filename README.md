# css-project
Practice css
# Three pillars to write good html and css.. and build good websites

    Responsive:
        Fluid layouts
        Media queries
        Responsive images
        Correct units
        Desktop-first and mobile-first
    
    Maintainable
        Clean
        Easy to understand
        Growth
        Reusable
        How to organize files
        How to name classes
        How to structure HTML
    
    Web performance
        Less HTTP requests
        Less code
        compress code
        Use a CSS preprocessor
        Less images
        Compress images


# What happends to css when we load up a webpage?

## 1.Load HTML-> 2.Parse HTML -------- -------> Document Object Model(DOM) ------->|
##           |                                                                  |
##           2.Load CSS ->  -Resolve conflicting CSS declarations(cascade)       | -> Render Tree ->   Website rendering: 
##                                                                          --->|                     The visual format
##                        - Process final css Values                                                  model    
   

# CSS value processing: what do you need to know
     Browsers specify a root font-size for each page(usually 16px)
     Percentages and relative values always converted to pixed( like: font-size: 150% (parent: 24px) ->  150*24 = 36px)
     Percentages are measured relative to their parent's WIDTH, if used to specify lengths( like: width: 60% (parent: 200px) ->  200*0.6 = 120px)
     EM are measured relative to their 'parent' font-size, if used to specify font-size;
     EM are measured relative to the 'current' font-size; if used to specify lengths;
     REM are always measured relative to the document's root font-size;
     VH and VW are simple percentage measurements of the viewport' height and with;


 