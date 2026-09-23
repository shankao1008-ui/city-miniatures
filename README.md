# Shenzhen, Kyoto & Da Nang, in miniature

A single-file Three.js app with three switchable cities: 15 places in Futian, Shenzhen; 15 around Gion and Higashiyama, Kyoto; and 15 from the Han River to My Khe Beach, Da Nang.

## Open the live website

[Explore City Miniatures — Shenzhen, Kyoto & Da Nang](https://shankao1008-ui.github.io/city-miniatures/)

Anyone can open this public HTML project in a modern WebGL-capable browser. No installation or GitHub account is required. Share the link above with others.

There is no build step. The application, styles, geometry, and destination data are all in `index.html`. Internet access is required to load Three.js 0.170.0 and OrbitControls from jsDelivr; no API key is needed.

[Open Da Nang directly](https://shankao1008-ui.github.io/city-miniatures/?city=danang)

## Explore and plan

Use the city selector in the header to switch between Shenzhen, China; Kyoto, Japan; and Da Nang, Vietnam without leaving the page. Each city has its own miniature, neighborhoods, filters, flight tour, map links, and saved itinerary. Switching resets the view and stops the tour. The last selected city is remembered in this browser.

- Drag to orbit; scroll or pinch to zoom. Right-drag or two-finger drag to pan.
- Select a labeled landmark or a place in the sidebar for visitor context and a map link.
- Search English or local names and filter by neighborhood or type.
- Start Flight Mode for a seven-stop camera tour. Interacting with the scene stops the tour; Escape closes panels and stops it.
- Add places to My itinerary. Reorder stops using the up arrows, remove stops, or export a text itinerary.
- The itinerary is saved in this browser’s local storage, for this website. Clearing browser storage removes it. Another browser or device has its own itinerary.
- Use the sun button for evening lighting and the home button to restore the overview. On narrow screens, open the place list with the menu button.

## Scope and accuracy

This is a stylized miniature, not a surveyed model or a turn-by-turn navigation service. Landmark coordinates are approximate; roads, surrounding buildings, roof shapes, and heights are simplified. The covered area spans about 3 km north–south in Shenzhen 2.5 km in Kyoto, and roughly 4 km in Da Nang. Da Nang covers the central riverfront and nearby coast; Ba Na Hills, Marble Mountains, and Son Tra Peninsula are outside this miniature. River crossings can add substantial walking distance; use a bridge and verify actual pedestrian routes. Park markers represent a viewpoint or approach, not every entrance. The museum and Civic Center share a complex.

Walking estimates use approximate geographic distance multiplied by 1.3, at 4.2 km/h. Lines show itinerary order rather than pedestrian routes. Crossings, indoor passages, park access, hills, and heat can substantially change travel time. Visit durations are planning suggestions, not opening hours. Confirm tickets, reservations, access, and current hours with the venue. No live availability or prices are represented.

The reference video was not present in the available workspace. The architecture is procedurally modeled from recognizable forms, rather than reconstructed from that video.

## Content references

- Official Da Nang tourism guide: https://danangfantasticity.com/en
- Da Nang local markets: https://danangfantasticity.com/en/night-market/famous-local-markets-in-danang

- Official Kyoto district guide: https://kyoto.travel/en/areas/gion-kiyomizu/
- Official Kyoto walking itinerary: https://kyoto.travel/en/itineraries/higashiyama-at-dawn/

- Shenzhen official visitor guide: https://www.sz.gov.cn/en_szgov/travel/
- Official Futian shopping guide: https://www.sz.gov.cn/en_szgov/news/infocus/SZCitywalk/Explore/Shopping/content/post_11961031.html
- Official civic-axis city walk: https://www.sz.gov.cn/en_szgov/news/infocus/SZCitywalk/Explore/CitywalkRoutes/GMC/content/post_11893508.html
- Cultural venues: https://www.sz.gov.cn/en_szgov/aboutsz/whatson/content/post_12404748.html

The app includes an official guide link and place-specific map searches. Map providers can apply different coordinate conventions in mainland China; use the destination name when confirming navigation.
