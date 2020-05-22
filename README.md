# The issue
Styles are not injected on SRR on development server

# How to reproduce
1. Run `npm run dev`
1. Open http://localhost:3000/
1. Text should be red
1. Disable JS on the page (e.g using the inspector)
1. Refresh the page

Text should still be red but instead is black, as styles are not being injected
