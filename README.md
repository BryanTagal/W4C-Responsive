# W4C-Responsive — Northbound Coffee

## Part 2: Three Clients, Three Branches

### Merge Order

I merged the three feature branches in the order of the client's priorities:

1. `feature/newsletter-signup` — highest priority
2. `feature/seasonal-colors` — medium priority
3. `feature/testimonial-expansion` — lowest priority

Each feature was developed and tested on its own branch before being merged into `main`.

### Merge Conflicts

I encountered merge conflicts when merging the seasonal colors branch and the testimonial expansion branch into `main`.

For the seasonal colors merge, there was a conflict in `css/style.css`. I resolved it manually by keeping the newsletter styles from `main` and combining them with the seasonal color changes.

For the testimonial expansion merge, there were conflicts in both `index.html` and `css/style.css`. I resolved them manually by keeping the newsletter, seasonal color, and testimonial changes together so all three client requests remained in the final site.

### Final Features

The final `main` branch includes:

- Newsletter signup with responsive mobile and desktop layouts
- Seasonal primary accent color
- Three responsive testimonials