[Uploading README.md…]()
# Family Meetup Map · Shanghai Disneyland

A self-contained static web game for families visiting Shanghai Disneyland. Parents can plan an attraction route while children explore a separate map. The game estimates movement and meetup timing from attraction wait times, ride durations, and configurable queue capacity. Each attraction also includes separate parent and child queue maps, with multiple child exploration routes.

## Project files

```text
family-meetup-map/
├── index.html   # Complete app, styles, interactions, and historical wait data
└── README.md    # Project documentation and GitHub Pages instructions
```

## Run locally

Open `index.html` in a modern web browser. No package installation, build step, or external JavaScript dependency is required. You can also serve the project with any static web server.

## Publish with GitHub Pages

1. Create an empty repository on GitHub.
2. Upload `index.html` and `README.md` to the repository root and commit them.
3. Open the repository’s **Settings → Pages** page.
4. Under **Build and deployment**, select **Deploy from a branch**, choose the `main` branch and `/(root)` folder, then save.
5. After deployment completes, open the site URL shown on the Pages settings page.

## Data and map notes

- Attraction wait baselines use Queue-Times’ 2025 annual average wait times for Shanghai Disney Resort. These are historical statistics, not live wait times. The queue model also lets users adjust ride duration, batch capacity, and the number of guests ahead.
- Attraction names are based on the [official Shanghai Disneyland attraction directory](https://www.shanghaidisneyresort.com/zh-cn/experience?group=attraction). The park illustration is informed by the [official park map](https://www.shanghaidisneyresort.com/zh-cn/maps/).
- The park and indoor queue layouts are simplified game schematics. They are not official navigation maps or facility floor plans. Follow park signage and the official app for current routes, operating status, and wait times.
- Wait-time data source: [Queue-Times · Shanghai Disney Resort 2025 attraction statistics](https://queue-times.com/en-US/parks/30/stats/2025?hide_archived=true).

## License

No license is included. Add a license file if you want to grant others permission to reuse or modify this project.
