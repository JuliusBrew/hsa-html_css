# 0x06 – CSS Grid | Checklist

Complete the required work before moving to the next module.



## 1. General Requirements

- [ ] All required files have been created
- [ ] Filenames are exactly as specified
- [ ] HTML files correctly link to their CSS files
- [ ] Code is cleanly formatted
- [ ] Layouts work as intended
- [ ] Work has been tested in the browser
- [ ] DevTools (Grid inspector) was used



## 2. Exercise: `0-grid_basics.html` + `0-grid_basics.css`

### Build
- [ ] Create a grid container
- [ ] Define columns with `grid-template-columns`
- [ ] Define rows (explicit or auto)
- [ ] Use `gap` for spacing
- [ ] Show a clear multi-column layout

### Check Your Understanding
- [ ] I can explain what a grid container and grid items are
- [ ] I understand the difference between columns and rows in Grid

### Test
- [ ] Layout matches the intention
- [ ] Tested in the browser



## 3. Exercise: `1-placement.html` + `1-placement.css`

### Build
- [ ] Places items using `grid-column` and/or `grid-row`
- [ ] Demonstrates spanning multiple tracks
- [ ] Creates a non-trivial layout (not just equal cells)
- [ ] Visual result clearly shows intentional placement

### Check Your Understanding
- [ ] I can explain how grid lines work
- [ ] I understand how to make an item span multiple columns/rows

### Test
- [ ] Placement works as expected
- [ ] Tested in the browser



## 4. Exercise: `2-grid_areas.html` + `2-grid_areas.css`

### Build
- [ ] Use `grid-template-areas`
- [ ] Assign areas to elements with `grid-area`
- [ ] Create a clear page-like structure (e.g. header / main / sidebar / footer)
- [ ] Code is readable thanks to named areas

### Check Your Understanding
- [ ] I can explain the benefit of named grid areas
- [ ] I understand how the areas string maps to the visual layout

### Test
- [ ] Layout matches the defined areas
- [ ] Tested in the browser



## 5. Exercise: `3-photo_gallery.html` + `3-photo_gallery.css`

### Build
- [ ] Gallery of images using CSS Grid
- [ ] Consistent gaps between items
- [ ] At least one item spans multiple cells (optional but recommended)
- [ ] Looks intentional and clean

### Check Your Understanding
- [ ] I can build a basic gallery with Grid
- [ ] I understand how Grid helps with equal or varied cell sizes

### Test
- [ ] Gallery displays correctly
- [ ] Tested in the browser



## 6. Exercise: `4-dashboard_layout.html` + `4-dashboard_layout.css`

### Build
- [ ] Dashboard-style layout (sidebar + main content + optional top bar/cards)
- [ ] Use Grid for the overall structure
- [ ] Multiple content sections/cards arranged intentionally
- [ ] Clean visual hierarchy

### Check Your Understanding
- [ ] I can structure a simple dashboard with Grid
- [ ] I know when to nest Flexbox inside Grid items

### Test
- [ ] Layout is clear and usable
- [ ] Tested in the browser



## 7. Project: `mini-project-magazine_layout.html` + `.css`

### Required Structure
- [ ] Semantic HTML
- [ ] External CSS file
- [ ] Use CSS Grid as the main layout method
- [ ] Must contain distinct regions (e.g. header, featured article, secondary articles, sidebar)

### Required Features
- [ ] Uses either line-based placement or named grid areas (or both)
- [ ] At least one element spans multiple columns or rows
- [ ] Clear visual hierarchy between featured and secondary content
- [ ] Consistent spacing with `gap`
- [ ] Polished enough to feel like a real section of a site

### Quality Check
- [ ] CSS is organized and readable
- [ ] Grid is used intentionally
- [ ] Layout works without relying on Flexbox for the overall structure
- [ ] Project feels complete for this level

### Optional Challenge
- [ ] Combine Grid (page structure) with Flexbox (internal component alignment)
- [ ] Create a more complex spanning pattern for a “featured” story
- [ ] Add a footer area into the grid



## 8. Knowledge Check

- [ ] What is the main difference between Flexbox and Grid?
- [ ] What does `grid-template-columns: 1fr 2fr 1fr` mean?
- [ ] How do you make an item span two columns?
- [ ] Why are named grid areas useful?
- [ ] When would you choose Grid over Flexbox?



## 9. Git & Submission

- [ ] All required files are present
- [ ] HTML files correctly link to CSS files
- [ ] Work has been tested
- [ ] Checklist is complete
- [ ] Changes committed and pushed
- [ ] Ready for review

### Suggested Commit

git add .
git commit -m "Complete 0x06-grid"
git push