<svg xmlns="http://www.w3.org/2000/svg" width="480" height="2052" class="">
    <defs>
        <style/>
    </defs>
    <style>/* SVG global context */
  svg {
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
    font-size: 14px;
    color: #777777;
  }

/* Large SVG context */
  svg.large .largeable {
    width: 474px;
  }
  svg.large .largeable &gt; .row {
    width: 100%;
  }
  svg.large .largeable-align-start {
    align-items: flex-start;
  }
  svg.large .column.largeable, svg.large .row.largeable, svg.large .largeable-inline-flex {
    display: inline-flex;
  }
  svg.large .largeable-flex-wrap, svg.large .largeable-column-fields {
    display: flex;
    flex-wrap: wrap;
  }
  svg.large .largeable-column-fields &gt; .field {
    width: 230px;
  }
  svg.large .chart.largeable {
    width: 458px;
  }
  svg.large .largeable-width-auto {
    width: auto;
  }
  svg.large .largeable-width-half {
    width: 50%;
  }

/* Headers */
  h1, h2, h3 {
    margin: 8px 0 2px;
    padding: 0;
    color: #0366d6;
    font-weight: normal;
  }
  h1 svg, h2 svg, h3 svg {
    fill: currentColor;
  }
  h1 {
    font-size: 20px;
    font-weight: bold;
  }
  h2 {
    font-size: 16px;
  }
  h3 {
    font-size: 14px;
  }

/* Fields */
  section &gt; .field {
    margin-left: 5px;
    margin-right: 5px;
  }
  .field {
    display: flex;
    align-items: center;
    margin-bottom: 2px;
    white-space: nowrap;
  }
  .field svg {
    margin: 0 8px;
    fill: #959da5;
    flex-shrink: 0;
  }
  .field.error {
    color: #cb2431;
  }
  .field.error svg {
    fill: #cb2431;
  }

/* Displays */
  .row {
    display: flex;
  }
  .row section {
    flex: 1 1 0;
  }
  .column {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .center {
    justify-content: center;
  }
  .horizontal {
    justify-content: space-around;
  }
  .horizontal-wrap {
    flex-wrap: wrap;
  }
  .horizontal .field {
    flex: 1 1 0;
  }
  .no-wrap {
    white-space: nowrap;
  }
  .fill-width {
    width: 100%;
  }
  .margin-bottom {
    margin-bottom: 16px;
  }
  .no-margin-top {
    margin-top: 0px;
  }

/* User avatar */
  .avatar {
    border-radius: 50%;
    margin: 0 6px;
  }

  .organization.avatar {
    border-radius: 15%;
  }

  .organization.name {
    white-space: nowrap;
  }

  .organization.contributions {
    margin: 0 8px;
    flex-wrap: wrap;
  }

  .contribution.organization {
    display: flex;
    border: 1px solid #959da5;
    border-radius: 6px;
    padding: 2px 6px;
    padding-left: 0;
    margin: 2px;
    font-size: 12px;
    background-color: #959da520;
  }

  .contribution.organization .avatar {
    margin: 0 4px;
  }

/* Commit calendar */
  .calendar.field {
    margin: 4px 0;
    margin-left: 7px;
  }
  .calendar .day {
    outline: 1px solid rgba(27,31,35,.04);
    outline-offset: -1px;
  }

/* Progress bars */
  svg.bar {
    margin: 4px 0;
  }

/* Language */
  .field.language {
    margin: 0 8px;
    flex-grow: 0;
  }

  .field.language.details {
    display: flex;
    justify-content: space-between;
  }

  .field.language.details small {
    display: flex;
    justify-content: space-between;
    color: #666666;
    text-align: right;
  }

  .field.language.details &gt; *, .field.language.details small &gt; * {
    flex: 1 1 0;
  }
  .field.language.details small &gt; *:not(:last-child) {
    margin-right: 6px;
  }

/* Follow-up */
  .followup.legend {
    font-size: 12px;
  }
  .followup.legend svg {
    margin: 0 3px;
    width: 14px;
    height: 14px;
  }
  .followup.legend svg:first-child {
    margin-left: 0;
  }
  .followup.legend svg:last-child {
    margin-right: 0;
  }

/* Labels */
  .label {
    background-color: #58A6FF30;
    color: #0366D6;
    padding: 0 10px;
    font-weight: 500;
    line-height: 22px;
    margin: 2px 5px;
    white-space: nowrap;
    border-radius: 32px;
    font-size: 12px;
  }

/* Habits */
  .habits {
    margin: 0;
    list-style-type: none;
    padding-left: 37px;
  }

/* Footer */
  footer {
    margin-top: 8px;
    font-size: 10px;
    font-style: italic;
    color: #666666;
    text-align: right;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 4px;
  }

/* Speed test categories */
  .categories {
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin-top: 4px;
  }
  .category {
    display: flex;
    flex-direction: column;
    align-items: center;
    flex: 1 1 0;
  }

/* Gauges */
  .gauge {
    stroke-linecap: round;
    fill: none;
  }
  .gauge.high {
    color: #18b663;
  }
  .gauge.average {
    color: #fb8c00;
  }
  .gauge.low {
    color: #e53935;
  }
  .gauge.info {
    color: #58A6FF;
  }
  .gauge-base, .gauge-arc {
    stroke: currentColor;
    stroke-width: 10;
  }
  .gauge-base {
    stroke-opacity: .2;
  }
  .gauge-arc {
    fill: none;
    stroke-dashoffset: 0;
    animation-delay: 250ms;
    animation: animation-gauge 1s ease forwards
  }
  .gauge text {
    fill: currentColor;
    font-size: 40px;
    font-family: monospace;
    text-anchor: middle;
    font-weight: 600;
  }
  .gauge .title {
    font-size: 18px;
    color: #777777;
  }
  @keyframes animation-gauge {
    from {
      stroke-dasharray: 0 329;
    }
  }
  .audits {
    margin-top: 8px;
  }
  .audit.text {
    min-width: 42px;
  }
  .audit svg {
    margin: 0;
  }
  .audit.high {
    fill: #18b663;
  }
  .audit.average {
    fill: #fb8c00;
  }
  .audit.low {
    fill: #e53935;
  }

  .screenshot {
    width: 452px;
    height: 315px;
    margin: 8px 14px 4px;
    border-radius: 5px;
  }

  svg.large .audits {
    display: inline-flex;
    width: 474px;
  }
  svg.large .audits section:last-child &gt; .field {
    justify-content: right;
  }
  svg.large .screenshot {
    width: 904px;
    height: 630px;
  }

/* Music plugin */
  .tracklist {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 28px;
    margin-top: 4px;
    width: 100%;
  }
  .track {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 4px;
  }
  .track img {
    margin: 0 10px;
    border-radius: 7px;
    flex-shrink: 0;
  }
  .track .name {
    font-size: 14px;
    line-height: 14px;
    font-weight: 600;
  }
  .track .artist, .track .played-at {
    font-size: 12px;
    color: #666666;
  }
  .track .infos {
    flex-grow: 1;
  }
  svg.large .tracklist {
    flex-direction: row;
    flex-wrap: wrap;
  }
  svg.large .track {
    width: 25%;
  }

/* Posts plugin */
  .post {
    align-items: flex-start;
  }
  .post .infos {
    display: flex;
    margin-bottom: 4px;
  }
  .post .infos .left {
    flex-shrink: 0;
    font-size: 12px;
    color: #666666;
    width: 72px;
    padding-top: 1px;
    text-align: center;
  }
  .post .infos .cover {
    width: 100%;
    height: 56px;
    background-position: center;
    background-size: cover;
    border-radius: 6px;
    overflow: hidden;
  }
  .post .infos .right {
    width: 376px;
    padding-left: 4px;
  }
  .post .infos .title, .post .infos .description {
    font-size: 14px;
    white-space: normal;
    overflow: hidden;
    text-overflow: ellipsis;
    max-height: 38px;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .post .infos .description {
    margin-top: 3px;
    font-size: 12px;
    max-height: 48px;
    color: #666666;
    -webkit-line-clamp: 3;
  }

/* Topics */
  .topics {
    display: flex;
    flex-wrap: wrap;
  }

  .topics img {
    border-radius: 5px;
    margin: 4px;
  }

/* Tweets */
  .tweet {
    font-size: 13px;
    margin-top: 6px;
    margin-bottom: 16px;
    margin-left: 18px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
  }

  .tweet .mention, .tweet .link, .tweet .hashtag {
    color: #0366d6;
  }

  .tweet .date {
    margin: 6px 0;
    font-size: 12px;
    color: #666666;
  }

  .tweet .attachments {
    display: flex;
    width: 450px;
    margin-top: 8px;
  }

  .tweet .attachments &gt; div {
    flex: 1 1 0;
    width: 0;
    border-radius: 6px;
    background-position: center;
    background-size: cover;
    height: 200px;
    margin: 2px;
    box-shadow: 0px 0px 1px #777777A0;
    overflow: hidden;
    display: flex;
    align-items: flex-end;
  }

  .tweet .attachments .infos {
    background-color: #000000D0;
    color: white;
    display: flex;
    flex-direction: column;
    width: 100%;
    padding-bottom: 4px;
  }

  .tweet .attachments .infos &gt; div {
    margin: 4px 8px 0;
  }

  .tweet .attachments .infos .title {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .tweet .attachments .infos .description {
    font-size: 11px;
    color: #666666;
  }

/* Charts and graphs */
  .chart {
    padding: 0 8px;
  }

  .chart-bars {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    width: 100%;
    margin: 8px 0 4px;
    flex-grow: 1;
    min-height: 70px;
  }

  .chart-bars .entry {
    flex: 1 1 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 10px;
    color: #666666;
  }

  .chart-bars .entry .value {
    font-size: 7px;
  }

  .chart-bars .entry .empty {
    width: 100%;
    text-align: center;
  }

  .chart-bars .bar {
    width: 7px;
    background-color: var(--color-calendar-graph-day-bg);
    border: 1px solid var(--color-calendar-graph-day-border);
    border-radius: 5px;
  }

  .chart-bars.horizontal {
    flex-direction: column;
    height: 100%;
  }

  .chart-bars.horizontal .entry {
    align-items: center;
    flex-direction: row;
    width: 100%;
    min-height: 1rem;
  }

  .chart-bars.horizontal .entry .name {
    flex-shrink: 0;
    text-align: right;
    width: 34%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .chart-bars .entry .bottom {
    margin-bottom: -1rem;
    line-height: 1rem;
  }

  .chart-bars.horizontal .bar {
    height: 7px;
    width: auto;
    margin: 0 6px;
  }

/* Repository */
  .repository {
    display: flex;
    flex-direction: column;
    width: 100%;
    margin: 6px 0;
  }

  .repository .name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 440px;
  }

  .repository .name span:first-child {
    color: #58a6ff;
  }

  .repository .name span:last-child {
    color: #666666;
    font-size: 10px;
  }

  .repository .description {
    display: block;
    width: 440px;
    white-space: normal;
  }

  .repository .description, .repository .infos {
    color: #666666;
    margin-left: 38px;
    font-size: 13px;
  }

  .repository .infos &gt; div {
    display: flex;
    align-items: center;
    margin-right: 16px;
  }

  .repository .infos svg {
    margin: 0;
    margin-right: 4px;
  }

/* Activity */
  .activity {
    margin-bottom: 12px;
  }

  .activity .field {
    width: 100%;
    overflow: hidden;
    text-overflow: ellipsis;
    max-width: 450px;
    white-space: nowrap;
    margin-bottom: 0;
  }

  .activity .field .content {
    flex-grow: 1;
    text-overflow: ellipsis;
    overflow: hidden;
  }

  .activity .repo, .activity .issue, .activity .commit .sha {
    display: inline;
    color: #58a6ff;
  }

  .activity .code {
    background-color: #7777771F;
    padding: 1px 5px;
    font-size: 80%;
    border-radius: 6px;
    color: #777777;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
    margin: 0 4px -3px;
  }

  .activity .bold, .activity .user {
    font-weight: 600;
  }

  .activity .details, .activity .timestamp {
    padding-left: 38px;
    display: flex;
    flex-direction: column;
    font-size: 13px;
    color: #666666;
  }

  .activity .timestamp {
    font-size: 10px;
    margin-top: 4px;
  }

  .activity .commit .sha {
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
  }

  .activity .commit .message {
    overflow: hidden;
    text-overflow: ellipsis;
    width: 360px;
    white-space: nowrap;
  }

  .activity .details &gt; .comment {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 420px;
    margin-top: 6px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

  svg.large .activity .field {
    max-width: 900px;
  }

/* People */
  .people {
    padding: 0 10px;
  }

  .people .avatar {
    margin: 0 2px;
  }

/* Projects */
  .project .description {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 420px;
    margin-left: 37px;
    max-height: 38px;
    font-size: 12px;
    white-space: normal;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

/* Anilist */
  .anilist {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 28px;
    margin-top: 4px;
  }

  .anilist .media {
    display: flex;
    margin-bottom: 4px;
    width: 450px;
  }
  .anilist .media img {
    margin: 0 10px;
    border-radius: 7px;
  }

  .anilist .media .about {
    flex-grow: 1;
  }
  .anilist .media .name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 14px;
    line-height: 14px;
    color: #58a6ff;
  }
  .anilist .media .infos {
    font-size: 12px;
    color: #666666;
  }
  .anilist .media .infos &gt; div {
    display: inline-flex;
    align-items: center;
    margin-right: 16px;
  }
  .anilist .media .infos svg {
    fill: currentColor;
    height: 12px;
    width: 12px;
    margin: 0;
    margin-right: 4px;
  }

  .anilist .media .description {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 380px;
    max-height: 38px;
    font-size: 12px;
    white-space: normal;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

  .anilist .characters {
    display: flex;
    flex-wrap: wrap;
  }

  .anilist .characters img {
    margin: 2px;
    border-radius: 7px;
  }

/* Licenses */
  .licenses {
    display: flex;
  }
  .licenses .column {
    align-items: flex-start;
    font-size: 12px;
    color: #666666;
    flex-shrink: 0;
  }
  .licenses-details {
    margin-top: 8px;
  }
  .field.license.details {
    display: flex;
    justify-content: space-between;
  }
  .field.license.details small {
    display: flex;
    justify-content: space-between;
    color: #666666;
    text-align: right;
  }
  .licenses .column:nth-child(1) {
    margin-left: 13px;
    width: 25%;
  }
  .licenses .column:nth-child(2) {
    width: 25%;
  }
  .licenses .column:nth-child(3) {
    width: 50%;
  }
  .licenses .column svg {
    height: 12px;
    width: 12px;
  }
  .licenses .column .title {
    font-weight: 600;
    margin-left: 15px;
  }
  .licenses .column .permission svg {
    fill: #56d364;
  }
  .licenses .column .limitation svg {
    fill: #f85149;
  }
  .licenses .column .condition svg {
    fill: #58a6ff;
  }

/* Contributors */
  .contributors {
    display: flex;
    flex-wrap: wrap;
    margin-left: 6px;
  }
  .contributors .label {
    padding-left: 0;
    display: flex;
    align-items: center;
  }
  .contributors .label img {
    margin-left: 0;
  }
  .contributors .contributions {
    display: flex;
    align-items: center;
    font-size: .7rem;
    margin-left: 6px;
    margin-right: -10px;
    background-color: #58A6FF10;
    padding: 0 7px;
    border-top-right-radius: 32px;
    border-bottom-right-radius: 32px;
  }
  .contributors .contributions svg {
    fill: #0366D6;
    margin-left: 4px;
    width: .8rem;
    height: .8rem;
  }

/* Introduction */
  .introduction {
    white-space: normal;
    margin: 0 13px 2px;
  }

/* Stackoverflow */
  .stackoverflow {
    margin-left: 38px;
  }
  .stackoverflow .entry {
    margin: 4px 0 12px;
  }
  .stackoverflow .title {
    color: #58a6ff;
    white-space: normal;
    align-items: flex-start;
  }
  .stackoverflow .body, .stackoverflow .infos {
    color: #666666;
    font-size: 13px;
    margin-left: 32px;
  }
  .stackoverflow .infos {
    display: flex;
    align-items: center;
  }
  .stackoverflow .infos &gt; div {
    display: inline-flex;
    align-items: center;
    margin-right: 16px;
  }
  .stackoverflow .infos svg {
    fill: currentColor;
    height: 12px;
    width: 12px;
    margin: 0;
    margin-right: 4px;
    flex-shrink: 0;
  }
  .stackoverflow .body {
    overflow: hidden;
    text-overflow: ellipsis;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
    width: 400px;
  }

/* Achievements */
  .achievement {
    display: flex;
    margin: 4px 0;
  }
  .achievement .icon {
    margin: 0 4px;
    width: 44px;
    height: 44px;
  }
  .achievement .text {
    font-size: 12px;
    color: #666666;
  }
  .achievement .unlock {
    font-size: 9px;
    color: #666666;
  }
  .achievement .title {
    font-size: 14px;
    color: #58A6FF;
  }
  .achievement .gauge.info {
    color: #58A6FF;
  }
  .achievement.x .title {
    color: #666666;
  }
  .achievement.x .gauge.info {
    color: #B0B0B0;
  }
  .achievement.b .title {
    color: #9D8FFF;
  }
  .achievement.b .gauge.info {
    color: #9E91FF;
  }
  .achievement.a .title {
    color: #D79533;
  }
  .achievement.a .gauge.info {
    color: #E7BD69;
  }
  .achievement.s .title {
    color: #FF0000;
  }
  .achievement.s .gauge.info {
    color: #FF0000;
  }
  .achievement.s .icon {
    filter: sepia() saturate(100);
  }
  .achievement.secret .title{
    color: #FF76CD;
  }
  .achievement.secret .gauge.info {
    color: #FF79D1;
  }
  .achievement .gh {
    border: 1px solid currentColor;
    border-radius: 16px;
    font-size: 10px;
    padding: 0 5px;
  }
  .achievement .gauge-base, .achievement .gauge-arc {
    stroke-width: 6;
  }

/* RSS feed */
  .rss {
    align-items: flex-start;
  }
  .rss .infos {
    margin-bottom: 3px;
  }
  .rss .infos .date {
    font-size: 10px;
    color: #666666;
  }

/* Skyline */
  .skyline-animation {
    margin: 2px 13px 6px;
    border-radius: 10px;
    background-color: #030D21;
    overflow: hidden;
  }

/* Markdown and syntax highlighting */
  .markdown b, .markdown i {
    display: inline-block;
    width: 97%;
  }
  code {
    background-color: #7777771F;
    display: inline-block;
    border-radius: 6px;
    color: #777777;
    padding: 1px 5px;
    font-size: 80%;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
  }
  code[class^=language-] {
    white-space: pre-wrap;
    width: 97%;
    margin-top: 4px;
  }
  .token.comment {
    color: #669900;
  }
  .token.punctuation {
    color: #8a93a8;
  }
  .token.namespace, .token.constant, .token.symbol, .token.keyword {
    color: #b44418;
  }
  .token.regex, .token.string, .token.char, .token.number, .token.boolean {
    color: #2777AA;
  }
  .token.property, .token.tag {
    color: #48428a;
  }
  .token.builtin, .token.operator {
    color: #106cbc;
  }
  .token.trimmed {
    font-style: italic;
    color: #77777760
  }

/* Charts */
  .ct-line {
    stroke-width: 2px !important;
    stroke: #58A6FF !important;
  }
  .ct-area {
    fill: #58A6FF !important;
  }
  .ct-label {
    fill: rgba(127, 127, 127, 0.8) !important;
    color: rgba(127, 127, 127, 0.8) !important;
  }
  .ct-grid {
    stroke: rgba(127, 127, 127, 0.4) !important;
  }

/* Autosize */
  .autosize {
    width: auto;
    height: auto;
  }

/* Fade animation */
  .af {
    opacity: 0;
    animation: animation-fade 1s ease forwards;
  }
  @keyframes animation-fade {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

/* Twemoji and GitHub emoji */
  .twemoji, .gemoji {
    height: 1em;
    width: 1em;
    margin-bottom: -.125em;
  }

/* Cake day */
  .cakeday, .cakeday svg {
    animation: animation-rainbow 1.2s;
    animation-iteration-count: infinite;
    animation-timing-function: steps(1);
  }

/* Rainbow animation */
  @keyframes animation-rainbow {
    0%, 100%{ color: #7F00FF; fill: #7F00FF; }
    14% { color: #A933FF; fill: #A933FF; }
    29%{ color: #007FFF; fill: #007FFF; }
    43%{ color: #00FF7F; fill: #00FF7F; }
		57%{ color: #FFFF00; fill: #FFFF00; }
		71%{ color: #FF7F00; fill: #FF7F00; }
		86%{ color: #FF0000; fill: #FF0000; }
  }

/* Calendar */
  :root {
    --color-calendar-graph-day-bg: #ebedf0;
    --color-calendar-graph-day-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-bg: #9be9a8;
    --color-calendar-graph-day-L2-bg: #40c463;
    --color-calendar-graph-day-L3-bg: #30a14e;
    --color-calendar-graph-day-L4-bg: #216e39;
    --color-calendar-halloween-graph-day-L1-bg: #ffee4a;
    --color-calendar-halloween-graph-day-L2-bg: #ffc501;
    --color-calendar-halloween-graph-day-L3-bg: #fe9600;
    --color-calendar-halloween-graph-day-L4-bg: #03001c;
    --color-calendar-graph-day-L4-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L3-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L2-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-border: rgba(27,31,35,0.06);
  }

/* End delimiter */
  #metrics-end {
    width: 100%;
  }

  .no-animations * {
    transition-delay: 0s !important;
    transition-duration: 0s !important;
    animation-delay: -0.0001s !important;
    animation-duration: 0s !important;
    animation-play-state: paused !important;
    caret-color: transparent !important;
  }</style>
    <foreignObject x="0" y="0" width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml" xmlns:xlink="http://www.w3.org/1999/xlink">
            <section>
                <h1 class="field">
                    <img class="avatar" src="data:image/png;base64,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" width="20" height="20" />
                    <span>HyRo</span>
                </h1>
                <div class="row">
                    <section>
                        <div class="field ">
            
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zm.5 4.75a.75.75 0 00-1.5 0v3.5a.75.75 0 00.471.696l2.5 1a.75.75 0 00.557-1.392L8.5 7.742V4.75z"/></svg>
              Joined GitHub 1 year ago
            
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"/></svg>
            Followed by 56 users
          </div>
                    </section>
                    <section>
                        <div class="field calendar">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 210 11" width="210" height="16">
                                <g>
                                    <rect class="day" x="0" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="15" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="30" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="45" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="60" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="75" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="90" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="105" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="120" y="0" width="11" height="11" fill="#40c463" rx="2" ry="2"/>
                                    <rect class="day" x="135" y="0" width="11" height="11" fill="#30a14e" rx="2" ry="2"/>
                                    <rect class="day" x="150" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="165" y="0" width="11" height="11" fill="#216e39" rx="2" ry="2"/>
                                    <rect class="day" x="180" y="0" width="11" height="11" fill="#40c463" rx="2" ry="2"/>
                                    <rect class="day" x="195" y="0" width="11" height="11" fill="#30a14e" rx="2" ry="2"/>
                                </g>
                            </svg>
                        </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1 2.5A2.5 2.5 0 013.5 0h8.75a.75.75 0 01.75.75v3.5a.75.75 0 01-1.5 0V1.5h-8a1 1 0 00-1 1v6.708A2.492 2.492 0 013.5 9h3.25a.75.75 0 010 1.5H3.5a1 1 0 100 2h5.75a.75.75 0 010 1.5H3.5A2.5 2.5 0 011 11.5v-9zm13.23 7.79a.75.75 0 001.06-1.06l-2.505-2.505a.75.75 0 00-1.06 0L9.22 9.229a.75.75 0 001.06 1.061l1.225-1.224v6.184a.75.75 0 001.5 0V9.066l1.224 1.224z"/></svg>
            Contributed to 65 repositories
          </div>
                    </section>
                </div>
            </section>
            <section class="largeable largeable-inline-flex">
                <div class="row">
                    <section>
                        <h2 class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"/></svg>
            Activity
          </h2>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/></svg>
            1032 Commits
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.5 1.75a.25.25 0 01.25-.25h8.5a.25.25 0 01.25.25v7.736a.75.75 0 101.5 0V1.75A1.75 1.75 0 0011.25 0h-8.5A1.75 1.75 0 001 1.75v11.5c0 .966.784 1.75 1.75 1.75h3.17a.75.75 0 000-1.5H2.75a.25.25 0 01-.25-.25V1.75zM4.75 4a.75.75 0 000 1.5h4.5a.75.75 0 000-1.5h-4.5zM4 7.75A.75.75 0 014.75 7h2a.75.75 0 010 1.5h-2A.75.75 0 014 7.75zm11.774 3.537a.75.75 0 00-1.048-1.074L10.7 14.145 9.281 12.72a.75.75 0 00-1.062 1.058l1.943 1.95a.75.75 0 001.055.008l4.557-4.45z"/></svg>
            33 Pull requests reviewed
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"/></svg>
            34 Pull requests opened
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"/></svg>
            38 Issues opened
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.75 2.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h2a.75.75 0 01.75.75v2.19l2.72-2.72a.75.75 0 01.53-.22h4.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25H2.75zM1 2.75C1 1.784 1.784 1 2.75 1h10.5c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0113.25 12H9.06l-2.573 2.573A1.457 1.457 0 014 13.543V12H2.75A1.75 1.75 0 011 10.25v-7.5z"/></svg>
            201 issue comments
          </div>
                    </section>
                    <section>
                        <h2 class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.326 1.973a1.2 1.2 0 011.49-.832c.387.112.977.307 1.575.602.586.291 1.243.71 1.7 1.296.022.027.042.056.061.084A13.22 13.22 0 018 3c.67 0 1.289.037 1.861.108l.051-.07c.457-.586 1.114-1.004 1.7-1.295a9.654 9.654 0 011.576-.602 1.2 1.2 0 011.49.832c.14.493.356 1.347.479 2.29.079.604.123 1.28.07 1.936.541.977.773 2.11.773 3.301C16 13 14.5 15 8 15s-8-2-8-5.5c0-1.034.238-2.128.795-3.117-.08-.712-.034-1.46.052-2.12.122-.943.34-1.797.479-2.29zM8 13.065c6 0 6.5-2 6-4.27C13.363 5.905 11.25 5 8 5s-5.363.904-6 3.796c-.5 2.27 0 4.27 6 4.27z"/><path d="M4 8a1 1 0 012 0v1a1 1 0 01-2 0V8zm2.078 2.492c-.083-.264.146-.492.422-.492h3c.276 0 .505.228.422.492C9.67 11.304 8.834 12 8 12c-.834 0-1.669-.696-1.922-1.508zM10 8a1 1 0 112 0v1a1 1 0 11-2 0V8z"/></svg>              Community stats
          </h2>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 14.25c0 .138.112.25.25.25H4v-1.25a.75.75 0 01.75-.75h2.5a.75.75 0 01.75.75v1.25h2.25a.25.25 0 00.25-.25V1.75a.25.25 0 00-.25-.25h-8.5a.25.25 0 00-.25.25v12.5zM1.75 16A1.75 1.75 0 010 14.25V1.75C0 .784.784 0 1.75 0h8.5C11.216 0 12 .784 12 1.75v12.5c0 .085-.006.168-.018.25h2.268a.25.25 0 00.25-.25V8.285a.25.25 0 00-.111-.208l-1.055-.703a.75.75 0 11.832-1.248l1.055.703c.487.325.779.871.779 1.456v5.965A1.75 1.75 0 0114.25 16h-3.5a.75.75 0 01-.197-.026c-.099.017-.2.026-.303.026h-3a.75.75 0 01-.75-.75V14h-1v1.25a.75.75 0 01-.75.75h-3zM3 3.75A.75.75 0 013.75 3h.5a.75.75 0 010 1.5h-.5A.75.75 0 013 3.75zM3.75 6a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM3 9.75A.75.75 0 013.75 9h.5a.75.75 0 010 1.5h-.5A.75.75 0 013 9.75zM7.75 9a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM7 6.75A.75.75 0 017.75 6h.5a.75.75 0 010 1.5h-.5A.75.75 0 017 6.75zM7.75 3a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5z"/></svg>
            Member of 2 organizations
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"/></svg>
            Following 3 users
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.25 2.5c-1.336 0-2.75 1.164-2.75 3 0 2.15 1.58 4.144 3.365 5.682A20.565 20.565 0 008 13.393a20.561 20.561 0 003.135-2.211C12.92 9.644 14.5 7.65 14.5 5.5c0-1.836-1.414-3-2.75-3-1.373 0-2.609.986-3.029 2.456a.75.75 0 01-1.442 0C6.859 3.486 5.623 2.5 4.25 2.5zM8 14.25l-.345.666-.002-.001-.006-.003-.018-.01a7.643 7.643 0 01-.31-.17 22.075 22.075 0 01-3.434-2.414C2.045 10.731 0 8.35 0 5.5 0 2.836 2.086 1 4.25 1 5.797 1 7.153 1.802 8 3.02 8.847 1.802 10.203 1 11.75 1 13.914 1 16 2.836 16 5.5c0 2.85-2.045 5.231-3.885 6.818a22.08 22.08 0 01-3.744 2.584l-.018.01-.006.003h-.002L8 14.25zm0 0l.345.666a.752.752 0 01-.69 0L8 14.25z"/></svg>
            Sponsoring 0 repositories
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"/></svg>
            Starred 23 repositories
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"/></svg>
            Watching 28 repositories
          </div>
                    </section>
                </div>
            </section>
            <section class="largeable largeable-inline-flex">
                <div class="row">
                    <section>
                        <h2 class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"/></svg>
          28 Repositories 
        </h2>
                        <div class="row">
                            <section>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"/></svg>
              
                Prefers MIT license
              
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"/></svg>
              13 Releases
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8.878.392a1.75 1.75 0 00-1.756 0l-5.25 3.045A1.75 1.75 0 001 4.951v6.098c0 .624.332 1.2.872 1.514l5.25 3.045a1.75 1.75 0 001.756 0l5.25-3.045c.54-.313.872-.89.872-1.514V4.951c0-.624-.332-1.2-.872-1.514L8.878.392zM7.875 1.69a.25.25 0 01.25 0l4.63 2.685L8 7.133 3.245 4.375l4.63-2.685zM2.5 5.677v5.372c0 .09.047.171.125.216l4.625 2.683V8.432L2.5 5.677zm6.25 8.271l4.625-2.683a.25.25 0 00.125-.216V5.677L8.75 8.432v5.516z"/></svg>
              0 Packages
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" d="M2.5 3.5c0-.133.058-.318.282-.55.227-.237.592-.484 1.1-.708C4.899 1.795 6.354 1.5 8 1.5c1.647 0 3.102.295 4.117.742.51.224.874.47 1.101.707.224.233.282.418.282.551 0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 5.205 9.646 5.5 8 5.5c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707-.224-.233-.282-.418-.282-.551zM1 3.5c0-.626.292-1.165.7-1.59.406-.422.956-.767 1.579-1.041C4.525.32 6.195 0 8 0c1.805 0 3.475.32 4.722.869.622.274 1.172.62 1.578 1.04.408.426.7.965.7 1.591v9c0 .626-.292 1.165-.7 1.59-.406.422-.956.767-1.579 1.041C11.476 15.68 9.806 16 8 16c-1.805 0-3.475-.32-4.721-.869-.623-.274-1.173-.62-1.579-1.04-.408-.426-.7-.965-.7-1.591v-9zM2.5 8V5.724c.241.15.503.286.779.407C4.525 6.68 6.195 7 8 7c1.805 0 3.475-.32 4.722-.869.275-.121.537-.257.778-.407V8c0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 9.705 9.646 10 8 10c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707C2.558 8.318 2.5 8.133 2.5 8zm0 2.225V12.5c0 .133.058.318.282.55.227.237.592.484 1.1.708 1.016.447 2.471.742 4.118.742 1.647 0 3.102-.295 4.117-.742.51-.224.874-.47 1.101-.707.224-.233.282-.418.282-.551v-2.275c-.241.15-.503.285-.778.406-1.247.549-2.917.869-4.722.869-1.805 0-3.475-.32-4.721-.869a6.236 6.236 0 01-.779-.406z"/></svg>
              304 MB used
            </div>
                            </section>
                            <section>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.25 2.5c-1.336 0-2.75 1.164-2.75 3 0 2.15 1.58 4.144 3.365 5.682A20.565 20.565 0 008 13.393a20.561 20.561 0 003.135-2.211C12.92 9.644 14.5 7.65 14.5 5.5c0-1.836-1.414-3-2.75-3-1.373 0-2.609.986-3.029 2.456a.75.75 0 01-1.442 0C6.859 3.486 5.623 2.5 4.25 2.5zM8 14.25l-.345.666-.002-.001-.006-.003-.018-.01a7.643 7.643 0 01-.31-.17 22.075 22.075 0 01-3.434-2.414C2.045 10.731 0 8.35 0 5.5 0 2.836 2.086 1 4.25 1 5.797 1 7.153 1.802 8 3.02 8.847 1.802 10.203 1 11.75 1 13.914 1 16 2.836 16 5.5c0 2.85-2.045 5.231-3.885 6.818a22.08 22.08 0 01-3.744 2.584l-.018.01-.006.003h-.002L8 14.25zm0 0l.345.666a.752.752 0 01-.69 0L8 14.25z"/></svg>
              0 Sponsors
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"/></svg>
              57 Stargazers
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"/></svg>
              35 Forkers
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"/></svg>
              30 Watchers
            </div>
                            </section>
                        </div>
                    </section>
                </div>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 2.75a.25.25 0 01.25-.25h12.5a.25.25 0 01.25.25v8.5a.25.25 0 01-.25.25h-6.5a.75.75 0 00-.53.22L4.5 14.44v-2.19a.75.75 0 00-.75-.75h-2a.25.25 0 01-.25-.25v-8.5zM1.75 1A1.75 1.75 0 000 2.75v8.5C0 12.216.784 13 1.75 13H3v1.543a1.457 1.457 0 002.487 1.03L8.061 13h6.189A1.75 1.75 0 0016 11.25v-8.5A1.75 1.75 0 0014.25 1H1.75zm5.03 3.47a.75.75 0 010 1.06L5.31 7l1.47 1.47a.75.75 0 01-1.06 1.06l-2-2a.75.75 0 010-1.06l2-2a.75.75 0 011.06 0zm2.44 0a.75.75 0 000 1.06L10.69 7 9.22 8.47a.75.75 0 001.06 1.06l2-2a.75.75 0 000-1.06l-2-2a.75.75 0 00-1.06 0z"/></svg>
      10 Languages
    </h2>
            </section>
            <section class="column">
                <h3 class="field">
        Most used languages
      </h3>
                <svg class="bar" xmlns="http://www.w3.org/2000/svg" width="460" height="8">
                    <mask id="languages-bar">
                        <rect x="0" y="0" width="460" height="8" fill="white" rx="5"/>
                    </mask>
                    <rect mask="url(#languages-bar)" x="0" y="0" width="0" height="8" fill="#d1d5da"/>
                    <rect mask="url(#languages-bar)" x="0" y="0" width="227.8050673024612" height="8" fill="#e34c26"/>
                    <rect mask="url(#languages-bar)" x="227.8050673024612" y="0" width="221.20960160051746" height="8" fill="#f1e05a"/>
                    <rect mask="url(#languages-bar)" x="449.01466890297866" y="0" width="5.638840627671603" height="8" fill="#563d7c"/>
                    <rect mask="url(#languages-bar)" x="454.65350953065024" y="0" width="3.7764778587563397" height="8" fill="#000080"/>
                    <rect mask="url(#languages-bar)" x="458.4299873894066" y="0" width="1.0013137079406624" height="8" fill="#a91e50"/>
                    <rect mask="url(#languages-bar)" x="459.4313010973473" y="0" width="0.4607253974342582" height="8" fill="#c6538c"/>
                    <rect mask="url(#languages-bar)" x="459.89202649478153" y="0" width="0.10537868132804841" height="8" fill="#89e051"/>
                    <rect mask="url(#languages-bar)" x="459.99740517610957" y="0" width="0.002594823890430741" height="8" fill="#C1F12E"/>
                </svg>
                <div class="field center horizontal-wrap fill-width">
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#e34c26" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                HTML
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#f1e05a" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                JavaScript
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#563d7c" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                CSS
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#000080" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                Lua
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#a91e50" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                EJS
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#c6538c" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                SCSS
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#89e051" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                Shell
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#C1F12E" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                Batchfile
              </div>
                </div>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.75 0A1.75 1.75 0 000 1.75v12.5C0 15.216.784 16 1.75 16h12.5A1.75 1.75 0 0016 14.25V1.75A1.75 1.75 0 0014.25 0H1.75zM1.5 1.75a.25.25 0 01.25-.25h12.5a.25.25 0 01.25.25v12.5a.25.25 0 01-.25.25H1.75a.25.25 0 01-.25-.25V1.75zM11.75 3a.75.75 0 00-.75.75v7.5a.75.75 0 001.5 0v-7.5a.75.75 0 00-.75-.75zm-8.25.75a.75.75 0 011.5 0v5.5a.75.75 0 01-1.5 0v-5.5zM8 3a.75.75 0 00-.75.75v3.5a.75.75 0 001.5 0v-3.5A.75.75 0 008 3z"/></svg>
      1 Project
    </h2>
                <div class="row">
                    <section class="project">
                        <div class="row fill-width">
                            <section>
                                <div class="field">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M0 3.75C0 2.784.784 2 1.75 2h12.5c.966 0 1.75.784 1.75 1.75v8.5A1.75 1.75 0 0114.25 14H1.75A1.75 1.75 0 010 12.25v-8.5zm1.75-.25a.25.25 0 00-.25.25v8.5c0 .138.112.25.25.25h12.5a.25.25 0 00.25-.25v-8.5a.25.25 0 00-.25-.25H1.75zM3.5 6.25a.75.75 0 01.75-.75h7a.75.75 0 010 1.5h-7a.75.75 0 01-.75-.75zm.75 2.25a.75.75 0 000 1.5h4a.75.75 0 000-1.5h-4z"/></svg>
                  Discord BOT [NODEJS]
                </div>
                            </section>
                        </div>
                        <div class="row">
                            <section>
                                <div class="field">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zm.5 4.75a.75.75 0 00-1.5 0v3.5a.75.75 0 00.471.696l2.5 1a.75.75 0 00.557-1.392L8.5 7.742V4.75z"/></svg>
                  Updated Oct 10 2020
                </div>
                            </section>
                            <section>
                                <div class="field">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.5 1.75a.25.25 0 01.25-.25h8.5a.25.25 0 01.25.25v7.736a.75.75 0 101.5 0V1.75A1.75 1.75 0 0011.25 0h-8.5A1.75 1.75 0 001 1.75v11.5c0 .966.784 1.75 1.75 1.75h3.17a.75.75 0 000-1.5H2.75a.25.25 0 01-.25-.25V1.75zM4.75 4a.75.75 0 000 1.5h4.5a.75.75 0 000-1.5h-4.5zM4 7.75A.75.75 0 014.75 7h2a.75.75 0 010 1.5h-2A.75.75 0 014 7.75zm11.774 3.537a.75.75 0 00-1.048-1.074L10.7 14.145 9.281 12.72a.75.75 0 00-1.062 1.058l1.943 1.95a.75.75 0 001.055.008l4.557-4.45z"/></svg>
                    12 done · 1 doing · 2 todo
                  </div>
                            </section>
                        </div>
                        <div class="field center horizontal-wrap ">
                            <svg class="bar" xmlns="http://www.w3.org/2000/svg" width="460" height="8">
                                <mask id="project-bar">
                                    <rect x="0" y="0" width="460" height="8" fill="white" rx="5"/>
                                </mask>
                                <rect mask="url(#project-bar)" x="0" y="0" width="368" height="8" fill="#28A745"/>
                                <rect mask="url(#project-bar)" x="368" y="0" width="30.666666666666668" height="8" fill="#6F42C1"/>
                                <rect mask="url(#project-bar)" x="398.6666666666667" y="0" width="61.333333333333336" height="8" fill="#d1d5da"/>
                            </svg>
                        </div>
                    </section>
                </div>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.75 1.5a.25.25 0 00-.25.25v12.5c0 .138.112.25.25.25h12.5a.25.25 0 00.25-.25V1.75a.25.25 0 00-.25-.25H1.75zM0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0114.25 16H1.75A1.75 1.75 0 010 14.25V1.75zm9.22 3.72a.75.75 0 000 1.06L10.69 8 9.22 9.47a.75.75 0 101.06 1.06l2-2a.75.75 0 000-1.06l-2-2a.75.75 0 00-1.06 0zM6.78 6.53a.75.75 0 00-1.06-1.06l-2 2a.75.75 0 000 1.06l2 2a.75.75 0 101.06-1.06L5.31 8l1.47-1.47z"/></svg>
      1 Gist
    </h2>
                <div class="row">
                    <section class="largeable-column-fields">
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4 1.75C4 .784 4.784 0 5.75 0h5.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v8.586A1.75 1.75 0 0114.25 15h-9a.75.75 0 010-1.5h9a.25.25 0 00.25-.25V6h-2.75A1.75 1.75 0 0110 4.25V1.5H5.75a.25.25 0 00-.25.25v2.5a.75.75 0 01-1.5 0v-2.5zm7.5-.188V4.25c0 .138.112.25.25.25h2.688a.252.252 0 00-.011-.013l-2.914-2.914a.272.272 0 00-.013-.011zM5.72 6.72a.75.75 0 000 1.06l1.47 1.47-1.47 1.47a.75.75 0 101.06 1.06l2-2a.75.75 0 000-1.06l-2-2a.75.75 0 00-1.06 0zM3.28 7.78a.75.75 0 00-1.06-1.06l-2 2a.75.75 0 000 1.06l2 2a.75.75 0 001.06-1.06L1.81 9.25l1.47-1.47z"/></svg>
            1 File
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.75 2.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h2a.75.75 0 01.75.75v2.19l2.72-2.72a.75.75 0 01.53-.22h4.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25H2.75zM1 2.75C1 1.784 1.784 1 2.75 1h10.5c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0113.25 12H9.06l-2.573 2.573A1.457 1.457 0 014 13.543V12H2.75A1.75 1.75 0 011 10.25v-7.5z"/></svg>
            0 Comments
          </div>
                    </section>
                    <section class="largeable-column-fields">
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"/></svg>
            1 Stargazer
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"/></svg>
            0 Forks
          </div>
                    </section>
                </div>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.75 0a.75.75 0 01.75.75V2h5V.75a.75.75 0 011.5 0V2h1.25c.966 0 1.75.784 1.75 1.75v10.5A1.75 1.75 0 0113.25 16H2.75A1.75 1.75 0 011 14.25V3.75C1 2.784 1.784 2 2.75 2H4V.75A.75.75 0 014.75 0zm0 3.5h8.5a.25.25 0 01.25.25V6h-11V3.75a.25.25 0 01.25-.25h2zm-2.25 4v6.75c0 .138.112.25.25.25h10.5a.25.25 0 00.25-.25V7.5h-11z"/></svg>
      Contributions calendar
    </h2>
                <div class="row">
                    <section>
                    </section>
                    <section>
                        <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M7.998 14.5c2.832 0 5-1.98 5-4.5 0-1.463-.68-2.19-1.879-3.383l-.036-.037c-1.013-1.008-2.3-2.29-2.834-4.434-.322.256-.63.579-.864.953-.432.696-.621 1.58-.046 2.73.473.947.67 2.284-.278 3.232-.61.61-1.545.84-2.403.633a2.788 2.788 0 01-1.436-.874A3.21 3.21 0 003 10c0 2.53 2.164 4.5 4.998 4.5zM9.533.753C9.496.34 9.16.009 8.77.146 7.035.75 4.34 3.187 5.997 6.5c.344.689.285 1.218.003 1.5-.419.419-1.54.487-2.04-.832-.173-.454-.659-.762-1.035-.454C2.036 7.44 1.5 8.702 1.5 10c0 3.512 2.998 6 6.498 6s6.5-2.5 6.5-6c0-2.137-1.128-3.26-2.312-4.438-1.19-1.184-2.436-2.425-2.653-4.81z"/></svg>
              Current streak 3 days
            </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path d="M8.5.75a.75.75 0 00-1.5 0v5.19L4.391 3.33a.75.75 0 10-1.06 1.061L5.939 7H.75a.75.75 0 000 1.5h5.19l-2.61 2.609a.75.75 0 101.061 1.06L7 9.561v5.189a.75.75 0 001.5 0V9.56l2.609 2.61a.75.75 0 101.06-1.061L9.561 8.5h5.189a.75.75 0 000-1.5H9.56l2.61-2.609a.75.75 0 00-1.061-1.06L8.5 5.939V.75z"/></svg>
            Best streak 32 days
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"/></svg>
            ~4.51 commits per day
          </div>
                    </section>
                </div>
                <svg version="1.1" xmlns="http://www.w3.org/2000/svg" style="margin-top: -52px;" viewBox="0,0 480,170">
                    <filter id="brightness1">
                        <feComponentTransfer>
                            <feFuncR type="linear" slope="0.6"/>
                            <feFuncG type="linear" slope="0.6"/>
                            <feFuncB type="linear" slope="0.6"/>
                        </feComponentTransfer>
                    </filter>
                    <filter id="brightness2">
                        <feComponentTransfer>
                            <feFuncR type="linear" slope="0.19999999999999996"/>
                            <feFuncG type="linear" slope="0.19999999999999996"/>
                            <feFuncB type="linear" slope="0.19999999999999996"/>
                        </feComponentTransfer>
                    </filter>
                    <g transform="scale(4) translate(12, 0)">
                        <g transform="translate(0, 0)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(1.7, 1)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(3.4, 2)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(5.1, 3)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.835616438356165)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1643835616438354 0,1.1643835616438356 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1643835616438356 1.7,2.1643835616438354 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(6.8, 4)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.917808219178081)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.917808219178081)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                        </g>
                        <g transform="translate(8.5, 5)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(10.2, 6)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.917808219178082)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.013698630136986)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9863013698630136 0,1.9863013698630136 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9863013698630136 1.7,2.9863013698630136 z"/>
                            </g>
                        </g>
                        <g transform="translate(11.9, 7)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(13.6, 8)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(15.299999999999999, 9)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(17, 10)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(18.7, 11)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.917808219178081)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(20.4, 12)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(22.099999999999998, 13)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.917808219178082)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(23.8, 14)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 4.534246575342466)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.465753424657534 0,3.4657534246575343 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.4657534246575343 1.7,4.465753424657534 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.684931506849315)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.315068493150685 0,2.315068493150685 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.315068493150685 1.7,3.315068493150685 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.917808219178081)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.178082191780822)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.821917808219178 0,1.821917808219178 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.821917808219178 1.7,2.821917808219178 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.835616438356166)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1643835616438354 0,1.1643835616438356 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1643835616438356 1.7,2.1643835616438354 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(25.5, 15)">
                            <g transform="translate(0, 5.095890410958905)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.904109589041096 0,1.904109589041096 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.904109589041096 1.7,2.904109589041096 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.671232876712329)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.328767123287671 0,1.3287671232876712 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3287671232876712 1.7,2.328767123287671 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.7534246575342465)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.2465753424657535 0,1.2465753424657535 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.2465753424657535 1.7,2.2465753424657535 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.917808219178081)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.424657534246576)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5753424657534247 0,1.5753424657534247 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5753424657534247 1.7,2.5753424657534247 z"/>
                            </g>
                        </g>
                        <g transform="translate(27.2, 16)">
                            <g transform="translate(0, 5.58904109589041)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.410958904109589 0,1.410958904109589 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.410958904109589 1.7,2.410958904109589 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.26027397260274)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.73972602739726 0,1.7397260273972601 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.7397260273972601 1.7,2.73972602739726 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(28.9, 17)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.013698630136986)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9863013698630136 0,1.9863013698630136 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9863013698630136 1.7,2.9863013698630136 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.835616438356165)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1643835616438354 0,1.1643835616438356 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1643835616438356 1.7,2.1643835616438354 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.835616438356166)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1643835616438354 0,1.1643835616438356 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1643835616438356 1.7,2.1643835616438354 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.58904109589041)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.410958904109589 0,1.410958904109589 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.410958904109589 1.7,2.410958904109589 z"/>
                            </g>
                        </g>
                        <g transform="translate(30.599999999999998, 18)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.095890410958905)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.904109589041096 0,1.904109589041096 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.904109589041096 1.7,2.904109589041096 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.58904109589041)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.410958904109589 0,1.410958904109589 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.410958904109589 1.7,2.410958904109589 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(32.3, 19)">
                            <g transform="translate(0, 5.013698630136986)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9863013698630136 0,1.9863013698630136 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9863013698630136 1.7,2.9863013698630136 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.917808219178082)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.178082191780822)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.821917808219178 0,1.821917808219178 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.821917808219178 1.7,2.821917808219178 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.013698630136986)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9863013698630136 0,1.9863013698630136 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9863013698630136 1.7,2.9863013698630136 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.849315068493151)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.1506849315068495 0,2.1506849315068495 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.1506849315068495 1.7,3.1506849315068495 z"/>
                            </g>
                            <g transform="translate(-10.2, 9.698630136986301)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.301369863013699 0,3.3013698630136985 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.3013698630136985 1.7,4.301369863013699 z"/>
                            </g>
                        </g>
                        <g transform="translate(34, 20)">
                            <g transform="translate(0, 4.438356164383562)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.5616438356164384 0,2.5616438356164384 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.5616438356164384 1.7,3.5616438356164384 z"/>
                            </g>
                            <g transform="translate(-1.7, 5.767123287671233)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.232876712328767 0,2.232876712328767 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.232876712328767 1.7,3.232876712328767 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.767123287671233)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.232876712328767 0,2.232876712328767 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.232876712328767 1.7,3.232876712328767 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.26027397260274)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.73972602739726 0,1.7397260273972601 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.7397260273972601 1.7,2.73972602739726 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.767123287671232)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.232876712328767 0,2.232876712328767 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.232876712328767 1.7,3.232876712328767 z"/>
                            </g>
                            <g transform="translate(-10.2, 10.356164383561644)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.643835616438356 0,2.643835616438356 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.643835616438356 1.7,3.643835616438356 z"/>
                            </g>
                        </g>
                        <g transform="translate(35.699999999999996, 21)">
                            <g transform="translate(0, 5.917808219178082)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.0821917808219177 0,1.0821917808219177 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.0821917808219177 1.7,2.0821917808219177 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.273972602739725)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.7260273972602738 0,2.7260273972602738 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.7260273972602738 1.7,3.7260273972602738 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.178082191780822)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.821917808219178 0,1.821917808219178 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.821917808219178 1.7,2.821917808219178 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.506849315068493)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.493150684931507 0,1.4931506849315068 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.4931506849315068 1.7,2.493150684931507 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.506849315068493)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.493150684931507 0,1.4931506849315068 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.4931506849315068 1.7,2.493150684931507 z"/>
                            </g>
                            <g transform="translate(-10.2, 9.78082191780822)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.219178082191781 0,3.219178082191781 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.219178082191781 1.7,4.219178082191781 z"/>
                            </g>
                        </g>
                        <g transform="translate(37.4, 22)">
                            <g transform="translate(0, 5.671232876712329)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.328767123287671 0,1.3287671232876712 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3287671232876712 1.7,2.328767123287671 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.342465753424658)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.6575342465753424 0,1.6575342465753424 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.6575342465753424 1.7,2.6575342465753424 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.438356164383562)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.5616438356164384 0,2.5616438356164384 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.5616438356164384 1.7,3.5616438356164384 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.506849315068493)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.493150684931507 0,1.4931506849315068 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.4931506849315068 1.7,2.493150684931507 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.342465753424658)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.6575342465753424 0,1.6575342465753424 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.6575342465753424 1.7,2.6575342465753424 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.424657534246576)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5753424657534247 0,1.5753424657534247 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5753424657534247 1.7,2.5753424657534247 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.67123287671233)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.328767123287671 0,1.3287671232876712 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3287671232876712 1.7,2.328767123287671 z"/>
                            </g>
                        </g>
                        <g transform="translate(39.1, 23)">
                            <g transform="translate(0, 5.835616438356165)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1643835616438354 0,1.1643835616438356 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1643835616438356 1.7,2.1643835616438354 z"/>
                            </g>
                            <g transform="translate(-1.7, 5.767123287671233)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.232876712328767 0,2.232876712328767 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.232876712328767 1.7,3.232876712328767 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.095890410958905)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.904109589041096 0,1.904109589041096 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.904109589041096 1.7,2.904109589041096 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.424657534246576)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5753424657534247 0,1.5753424657534247 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5753424657534247 1.7,2.5753424657534247 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.835616438356166)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1643835616438354 0,1.1643835616438356 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1643835616438356 1.7,2.1643835616438354 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.520547945205479)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.4794520547945202 0,2.4794520547945202 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.4794520547945202 1.7,3.4794520547945202 z"/>
                            </g>
                            <g transform="translate(-10.2, 6)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,8 0,7 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,7 1.7,8 z"/>
                            </g>
                        </g>
                        <g transform="translate(40.8, 24)">
                            <g transform="translate(0, 4.356164383561644)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.643835616438356 0,2.643835616438356 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.643835616438356 1.7,3.643835616438356 z"/>
                            </g>
                            <g transform="translate(-1.7, 4.452054794520548)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.5479452054794525 0,3.547945205479452 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.547945205479452 1.7,4.5479452054794525 z"/>
                            </g>
                            <g transform="translate(-3.4, 5.945205479452055)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.054794520547945 0,3.054794520547945 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.054794520547945 1.7,4.054794520547945 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.109589041095891)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.8904109589041096 0,2.8904109589041096 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.8904109589041096 1.7,3.8904109589041096 z"/>
                            </g>
                            <g transform="translate(-6.8, 6.136986301369863)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,5.863013698630137 0,4.863013698630137 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,4.863013698630137 1.7,5.863013698630137 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.26027397260274)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.73972602739726 0,1.7397260273972601 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.7397260273972601 1.7,2.73972602739726 z"/>
                            </g>
                            <g transform="translate(-10.2, 9.36986301369863)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.63013698630137 0,3.6301369863013697 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.6301369863013697 1.7,4.63013698630137 z"/>
                            </g>
                        </g>
                        <g transform="translate(42.5, 25)">
                            <g transform="translate(0, 4.273972602739725)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.7260273972602738 0,2.7260273972602738 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.7260273972602738 1.7,3.7260273972602738 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.58904109589041)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.410958904109589 0,1.410958904109589 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.410958904109589 1.7,2.410958904109589 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.424657534246576)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5753424657534247 0,1.5753424657534247 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5753424657534247 1.7,2.5753424657534247 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.424657534246576)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5753424657534247 0,1.5753424657534247 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5753424657534247 1.7,2.5753424657534247 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.506849315068493)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.493150684931507 0,1.4931506849315068 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.4931506849315068 1.7,2.493150684931507 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.67123287671233)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.328767123287671 0,1.3287671232876712 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3287671232876712 1.7,2.328767123287671 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(44.199999999999996, 26)">
                            <g transform="translate(0, 5.7534246575342465)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.2465753424657535 0,1.2465753424657535 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.2465753424657535 1.7,2.2465753424657535 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.424657534246576)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5753424657534247 0,1.5753424657534247 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5753424657534247 1.7,2.5753424657534247 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.342465753424658)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.6575342465753424 0,1.6575342465753424 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.6575342465753424 1.7,2.6575342465753424 z"/>
                            </g>
                        </g>
                    </g>
                </svg>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M0 8a8 8 0 1116 0v5.25a.75.75 0 01-1.5 0V8a6.5 6.5 0 10-13 0v5.25a.75.75 0 01-1.5 0V8zm5.5 4.25a.75.75 0 01.75-.75h3.5a.75.75 0 010 1.5h-3.5a.75.75 0 01-.75-.75zM3 6.75C3 5.784 3.784 5 4.75 5h6.5c.966 0 1.75.784 1.75 1.75v1.5A1.75 1.75 0 0111.25 10h-6.5A1.75 1.75 0 013 8.25v-1.5zm1.47-.53a.75.75 0 011.06 0l.97.97.97-.97a.75.75 0 011.06 0l.97.97.97-.97a.75.75 0 111.06 1.06l-1.5 1.5a.75.75 0 01-1.06 0L8 7.81l-.97.97a.75.75 0 01-1.06 0l-1.5-1.5a.75.75 0 010-1.06z"/></svg>
      Recent activity
    </h2>
                <div class="row">
                    <section>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">CDN-Github/CDN-1</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">main</span></div>
                                    <div class="commit">
                                        <span class="sha">#109d9bc</span>
                                        <span class="message">Create PluginInstallScript.exe</span>
                                    </div>
                                </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">CDN-Github/CDN-1</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">main</span></div>
                                    <div class="commit">
                                        <span class="sha">#fcb9a91</span>
                                        <span class="message">Delete version.txt</span>
                                    </div>
                                </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">CDN-Github/CDN-1</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">main</span></div>
                                    <div class="commit">
                                        <span class="sha">#6f685f9</span>
                                        <span class="message">Create version.txt</span>
                                    </div>
                                </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">CDN-Github/CDN-1</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">main</span></div>
                                    <div class="commit">
                                        <span class="sha">#97142cf</span>
                                        <span class="message">Delete x.t</span>
                                    </div>
                                </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">CDN-Github/CDN-1</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">main</span></div>
                                    <div class="commit">
                                        <span class="sha">#137bf26</span>
                                        <span class="message">Add files via upload</span>
                                    </div>
                                </div>
                            </section>
                        </div>
                    </section>
                </div>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path d="M8.5.75a.75.75 0 00-1.5 0v5.19L4.391 3.33a.75.75 0 10-1.06 1.061L5.939 7H.75a.75.75 0 000 1.5h5.19l-2.61 2.609a.75.75 0 101.061 1.06L7 9.561v5.189a.75.75 0 001.5 0V9.56l2.609 2.61a.75.75 0 101.06-1.061L9.561 8.5h5.189a.75.75 0 000-1.5H9.56l2.61-2.609a.75.75 0 00-1.061-1.06L8.5 5.939V.75z"/></svg>
      Achievements
    </h2>
                <div class="row">
                    <section class="largeable-flex-wrap">
                        <div class="achievement a largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="0 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-linecap="round" stroke-width="2" fill="none" fill-rule="evenodd">
                                            <path d="M17.135 7.988l-3.303.669a2 2 0 00-1.586 2.223l4.708 35.392a1.498 1.498 0 01-1.162 1.66 1.523 1.523 0 01-1.775-1.01L4.951 19.497a2 2 0 011.215-2.507l2.946-1.072" stroke="#FFD576" stroke-linejoin="round"/>
                                            <path d="M36.8 48H23a2 2 0 01-2-2V7a2 2 0 012-2h26a2 2 0 012 2v32.766" stroke="#B59151"/>
                                            <path d="M29 20.955l-3.399 3.399a.85.85 0 000 1.202l3.399 3.4M43.014 20.955l3.399 3.399a.85.85 0 010 1.202l-3.4 3.4" stroke="#B59151" stroke-linejoin="round"/>
                                            <path stroke="#B59151" d="M38.526 18l-5.053 14.016"/>
                                            <path d="M44 36a8 8 0 110 16 8 8 0 010-16z" stroke="#B59151" stroke-linejoin="round"/>
                                            <path d="M43.068 40.749l3.846 2.396a1 1 0 01-.006 1.7l-3.846 2.36a1 1 0 01-1.523-.853v-4.755a1 1 0 011.529-.848z" stroke="#B59151" stroke-linejoin="round"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Super polyglot
                  
                </div>
                                <div class="text">Using 8 different programming languages</div>
                            </div>
                        </div>
                        <div class="achievement b largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="0 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-linecap="round" stroke-width="2" fill="none" fill-rule="evenodd">
                                            <g stroke="#B2A8FF" stroke-linejoin="round">
                                                <path d="M30 51H16.543v-2.998h-4v2.976l-5.537.016a2 2 0 01-2.006-2v-8.032a2 2 0 01.75-1.562l9.261-7.406 5.984 5.143m29.992 3.864v10h-6v-3h-5v3h-6m-.987-33c.133-1.116.793-2.106 1.978-2.968.44-.32 5.776-3.664 16.01-10.032v36"/>
                                                <path d="M19 34.994v-8.982m16 0V49a2 2 0 01-2 2h-8.987l.011-6.957"/>
                                            </g>
                                            <path stroke="#B2A8FF" d="M40 38h5M40 34h5"/>
                                            <path stroke="#7D6CFF" d="M25 30h5M25 34h5M25 26h5"/>
                                            <path d="M35.012 22.003H9.855a4.843 4.843 0 010-9.686h1.479c1.473-4.268 4.277-6.674 8.41-7.219 6.493-.856 9.767 4.27 10.396 5.9.734-.83 2.137-2.208 4.194-1.964a4.394 4.394 0 011.685.533" stroke="#7D6CFF" stroke-linejoin="round"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Great worker
                  
                </div>
                                <div class="text">Joined 2 organizations</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="138.68421052631578 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-linecap="round" stroke-width="2" fill="none" fill-rule="evenodd">
                                            <g stroke="#2088FF">
                                                <path d="M20 24l-3.397 3.398a.85.85 0 000 1.203L20.002 32M37.015 24l3.399 3.398a.85.85 0 010 1.203L37.014 32" stroke-linejoin="round"/>
                                                <path d="M31.029 21.044L25.976 35.06"/>
                                            </g>
                                            <path stroke="#79B8FF" stroke-linejoin="round" d="M23.018 10h8.984M26 47h5M8 16h16m9 0h15.725M8 41h13"/>
                                            <path d="M5.027 34.998c.673 2.157 1.726 4.396 2.81 6.02m43.38-19.095C50.7 19.921 49.866 17.796 48.79 16" stroke="#79B8FF"/>
                                            <path stroke="#2088FF" stroke-linejoin="round" d="M26 41h17"/>
                                            <path d="M7.183 16C5.186 19.582 4 23.619 4 28M42.608 47.02c2.647-1.87 5.642-5.448 7.295-9.18C51.52 34.191 52.071 30.323 52 28" stroke="#2088FF"/>
                                            <path stroke="#2088FF" stroke-linejoin="round" d="M7.226 16H28M13.343 47H21"/>
                                            <path d="M13.337 47.01a24.364 24.364 0 006.19 3.45 24.527 24.527 0 007.217 1.505c2.145.108 4.672-.05 7.295-.738" stroke="#2088FF"/>
                                            <path stroke="#2088FF" stroke-linejoin="round" d="M36 47h6.647M12 10h6M37 10h6.858"/>
                                            <path d="M43.852 10c-4.003-3.667-9.984-6.054-16.047-6-2.367.021-4.658.347-6.81 1.045" stroke="#2088FF"/>
                                            <path stroke="#79B8FF" stroke-linejoin="round" d="M5.041 35h4.962M47 22h4.191"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Developer
                  
                    <span class="gh">
                      ranked 1.81m out of 74m users
                    </span>
                  
                </div>
                                <div class="text">Published 18 public repositories</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="77.5 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-width="2" fill="none" fill-rule="evenodd">
                                            <path d="M37.303 21.591a5.84 5.84 0 00-1.877-1.177 6.138 6.138 0 00-4.432 0 5.822 5.822 0 00-1.879 1.177L28 22.638l-1.115-1.047c-1.086-1.018-2.559-1.59-4.094-1.59-1.536 0-3.008.572-4.094 1.59-1.086 1.02-1.696 2.4-1.696 3.84 0 1.441.61 2.823 1.696 3.841l1.115 1.046L28 38l8.189-7.682 1.115-1.046a5.422 5.422 0 001.256-1.761 5.126 5.126 0 000-4.157 5.426 5.426 0 00-1.256-1.763z" stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M15.967 42.705A18.922 18.922 0 0028 47a18.92 18.92 0 0011.076-3.56m-.032-30.902A18.914 18.914 0 0028 9c-4.09 0-7.876 1.292-10.976 3.49" stroke="#79B8FF" stroke-linecap="round"/>
                                            <g transform="translate(7 10)" stroke="#2088FF">
                                                <path d="M6 0v7c0 2.21-1.343 3-3 3s-3-.79-3-3V0" stroke-linecap="round" stroke-linejoin="round"/>
                                                <path stroke-linecap="round" d="M3 0v19.675"/>
                                                <rect stroke-linejoin="round" x="1" y="20" width="4" height="16" rx="2"/>
                                            </g>
                                            <g transform="translate(43 10)" stroke="#2088FF">
                                                <path stroke-linecap="round" d="M2 15.968v3.674"/>
                                                <path d="M4 15.642H0L.014 4.045A4.05 4.05 0 014.028 0L4 15.642z" stroke-linecap="round" stroke-linejoin="round"/>
                                                <rect stroke-linejoin="round" y="19.968" width="4" height="16" rx="2"/>
                                            </g>
                                            <path d="M41.364 8.062A23.888 23.888 0 0028 4a23.89 23.89 0 00-11.95 3.182M4.75 22.021A24.045 24.045 0 004 28c0 1.723.182 3.404.527 5.024m10.195 14.971A23.888 23.888 0 0028 52c4.893 0 9.444-1.464 13.239-3.979m9-10.98A23.932 23.932 0 0052 28c0-2.792-.477-5.472-1.353-7.964" stroke="#79B8FF" stroke-linecap="round"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Forker
                  
                </div>
                                <div class="text">Forked 3 public repositories</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="57.790368818572425 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g xmlns="http://www.w3.org/2000/svg" transform="translate(5 4)" fill="none" fill-rule="evenodd">
                                            <path d="M46 44.557v1a2 2 0 01-2 2H2a2 2 0 01-2-2v-1" stroke="#79B8FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M.75 40.993l.701.561a2.323 2.323 0 002.903 0l1.675-1.34a3 3 0 013.748 0l1.282 1.026a3 3 0 003.71.03l1.4-1.085a3 3 0 013.75.061l1.103.913a3 3 0 003.787.031l1.22-.976a3 3 0 013.748 0l1.282 1.026a3 3 0 003.71.03l1.4-1.085a3 3 0 013.75.061l1.429 1.182a2.427 2.427 0 003.103-.008l.832-.695A2 2 0 0046 39.191v-1.634a2 2 0 00-2-2H2a2 2 0 00-2 2v1.875a2 2 0 00.75 1.561z" stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M42 31.609v.948m-38 0v-.992m25.04-15.008H35a2 2 0 012 2v1m-28 0v-1a2 2 0 012-2h6.007" stroke="#79B8FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M22 8.557h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6a1 1 0 011-1z" stroke="#2088FF" stroke-width="2" stroke-linejoin="round"/>
                                            <path d="M4.7 10.557c.316 1.122.572 1.372 1.71 1.678-1.136.314-1.39.566-1.7 1.69-.317-1.121-.573-1.372-1.71-1.679 1.135-.313 1.389-.566 1.7-1.689zm35-8c.316 1.122.572 1.372 1.71 1.678-1.136.314-1.39.566-1.7 1.69-.317-1.121-.573-1.372-1.71-1.679 1.135-.313 1.389-.566 1.7-1.689z" stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M23 5.557a2 2 0 002-2C25 2.452 24.433 0 22.273 0c-.463 0 .21 1.424-.502 1.979A2 2 0 0023 5.557z" stroke="#2088FF" stroke-width="2"/>
                                            <path d="M4.78 27.982l1.346 1.076a3 3 0 003.748 0l1.252-1.002a3 3 0 013.748 0l1.282 1.026a3 3 0 003.711.03l1.4-1.085a3 3 0 013.75.061l1.102.913a3 3 0 003.787.031l1.22-.976a3 3 0 013.748 0l1.281 1.025a3 3 0 003.712.029l1.358-1.053a2 2 0 00.775-1.58v-.97a1.95 1.95 0 00-1.95-1.95H5.942a1.912 1.912 0 00-1.912 1.912v.951a2 2 0 00.75 1.562z" stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <circle stroke="#79B8FF" cx="16.5" cy="2.057" r="1"/>
                                            <circle stroke="#79B8FF" cx="14.5" cy="12.057" r="1"/>
                                            <circle stroke="#79B8FF" cx="31.5" cy="9.057" r="1"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Member
                  
                </div>
                                <div class="text">Registered 1 year ago</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="42.83919597989949 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g transform="translate(4 4)" stroke-width="2" fill="none" fill-rule="evenodd">
                                            <path d="M33.432 1.924A23.922 23.922 0 0024 0c-3.945 0-7.668.952-10.95 2.638m-9.86 9.398A23.89 23.89 0 000 24a23.9 23.9 0 002.274 10.21m3.45 5.347a23.992 23.992 0 0012.929 7.845m13.048-.664c4.43-1.5 8.28-4.258 11.123-7.848m3.16-5.245A23.918 23.918 0 0048 24c0-1.87-.214-3.691-.619-5.439M40.416 6.493a24.139 24.139 0 00-1.574-1.355" stroke="#79B8FF" stroke-linecap="round"/>
                                            <path stroke="#79B8FF" d="M4.582 33.859l1.613-7.946"/>
                                            <circle stroke="#79B8FF" cx="6.832" cy="23" r="3"/>
                                            <path stroke="#2088FF" d="M17.444 39.854l4.75 3.275"/>
                                            <path stroke="#79B8FF" stroke-linecap="round" d="M7.647 14.952l-.433 4.527"/>
                                            <circle stroke="#2088FF" cx="15" cy="38" r="3"/>
                                            <path stroke="#2088FF" d="M22.216 9.516l.455 4.342"/>
                                            <path stroke="#79B8FF" stroke-linecap="round" d="M34.272 6.952l-2.828 5.25"/>
                                            <path stroke="#2088FF" stroke-linecap="square" d="M11.873 7.235l6.424-.736"/>
                                            <path stroke="#79B8FF" stroke-linecap="round" d="M28.811 5.445l3.718-.671"/>
                                            <path stroke="#2088FF" d="M42.392 22.006l.456-5.763M34.349 24.426l4.374.447"/>
                                            <path d="M20 28c.267-1.727 1.973-3 4-3 2.08 0 3.787 1.318 4 3m-4-9a3 3 0 110 6 3 3 0 010-6z" stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M24 14c5.523 0 10 4.477 10 10s-4.477 10-10 10-10-4.477-10-10 4.477-10 10-10z" stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round"/>
                                            <circle stroke="#79B8FF" cx="35.832" cy="4" r="3"/>
                                            <circle stroke="#79B8FF" cx="44" cy="36" r="3"/>
                                            <circle stroke="#79B8FF" cx="34.832" cy="37" r="3"/>
                                            <circle stroke="#2088FF" cx="21.654" cy="6.437" r="3"/>
                                            <path d="M25.083 48.102a3 3 0 100-6 3 3 0 000 6z" stroke="#2088FF"/>
                                            <path d="M8.832 5a3 3 0 110 6 3 3 0 010-6z" stroke="#2088FF" stroke-linecap="round"/>
                                            <circle stroke="#79B8FF" cx="4" cy="37" r="3"/>
                                            <path d="M42.832 10a3 3 0 110 6 3 3 0 010-6z" stroke="#2088FF" stroke-linecap="round"/>
                                            <path stroke="#79B8FF" stroke-linecap="round" d="M32.313 38.851l-1.786 1.661"/>
                                            <circle stroke="#2088FF" cx="42" cy="25" r="3"/>
                                            <path stroke="#2088FF" stroke-linecap="square" d="M18.228 32.388l-1.562 2.66"/>
                                            <path stroke="#79B8FF" d="M37.831 36.739l2.951-.112"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Influencer
                  
                    <span class="gh">
                      ranked 107k out of 74m users
                    </span>
                  
                </div>
                                <div class="text">Followed by 56 users</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="30.37688442211055 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-width="2" fill="none" fill-rule="evenodd">
                                            <path stroke="#79B8FF" stroke-linecap="round" stroke-linejoin="round" d="M26.022 5.014h6M26.012 53.005h6M27.003 47.003h12M44.01 20.005h5M19.01 11.003h12"/>
                                            <path stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round" d="M38.005 11.008h6M41 14.013v-6M14.007 47.003h6M17.002 50.004v-6"/>
                                            <path d="M29.015 5.01l-5.003 5.992 5.003-5.992zM33.015 47.01l-5.003 5.992 5.003-5.992z" stroke="#79B8FF"/>
                                            <path stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round" d="M8.01 19.002h6"/>
                                            <path stroke="#79B8FF" stroke-linecap="round" stroke-linejoin="round" d="M47.011 29h6"/>
                                            <path stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round" d="M44.012 39.003h6"/>
                                            <g stroke="#79B8FF">
                                                <path d="M5.36 29c4.353 0 6.4 4.472 6.4 8"/>
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M13.99 37.995h-5M10.989 29h-6"/>
                                            </g>
                                            <path d="M24.503 22c1.109 0 2.007.895 2.007 2 0 1.104-.898 2-2.007 2a2.004 2.004 0 01-2.008-2c0-1.105.9-2 2.008-2zM24.5 32a2 2 0 110 4 2 2 0 010-4zm9.5 0a2 2 0 110 4 2 2 0 010-4z" stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path stroke="#2088FF" d="M24.5 26.004v6.001"/>
                                            <path d="M31.076 23.988l1.027-.023a1.998 1.998 0 011.932 2.01L34 31" stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round" d="M31.588 26.222l-2.194-2.046 2.046-2.194"/>
                                            <path d="M29.023 43c7.732 0 14-6.268 14-14s-6.268-14-14-14-14 6.268-14 14 6.268 14 14 14z" stroke="#2088FF"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Contributor
                  
                </div>
                                <div class="text">Opened 40 pull requests</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="24.92462311557789 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-linecap="round" stroke-width="2" fill="none" fill-rule="evenodd">
                                            <g stroke="#79B8FF">
                                                <path d="M26.009 34.01c.444-.004.9.141 1.228.414.473.394.766.959.76 1.54-.01.735-.333 1.413-.97 2.037.66.718.985 1.4.976 2.048-.012.828-.574 1.58-1.687 2.258.624.788.822 1.549.596 2.28-.225.733-.789 1.219-1.69 1.459.703.833.976 1.585.82 2.256-.178.763-.313 1.716-2.492 1.711" stroke-linejoin="round"/>
                                                <g stroke-linejoin="round">
                                                    <path d="M18.548 28.422c1.184-4.303-2.132-5.292-2.132-5.292-.873 2.296-1.438 3.825-4.231 8.108-1.285 1.97-1.926 3.957-1.877 5.796M18.391 34.011L24.993 34c2.412-.009.211-.005-6.602.012zM5.004 37.017l5.234-.014-5.234.014z"/>
                                                </g>
                                                <g stroke-linejoin="round">
                                                    <path d="M18.548 28.422c1.184-4.303-2.132-5.292-2.132-5.292-.873 2.296-1.438 3.825-4.231 8.108-1.285 1.97-1.926 3.957-1.877 5.796M5.004 37.017l5.234-.014-5.234.014zM7 48.012h4.01c1.352 1.333 2.672 2 3.961 2.001 0 0 .485-.005 5.46-.005h3.536"/>
                                                </g>
                                                <path d="M18.793 27.022c-.062.933-.373 2.082-.933 3.446-.561 1.364-.433 2.547.383 3.547"/>
                                            </g>
                                            <path d="M45 16.156V23a2 2 0 01-2 2H31l-6 4v-4h-1.934M12 23V8a2 2 0 012-2h29a2 2 0 012 2v10" stroke="#2088FF" stroke-linejoin="round"/>
                                            <path stroke="#2088FF" stroke-linejoin="round" d="M23 12.014l-3 3 3 3M34 12.014l3 3-3 3"/>
                                            <path stroke="#2088FF" d="M30.029 10l-3.015 10.027"/>
                                            <path d="M32 39h3l6 4v-4h8a2 2 0 002-2V22a2 2 0 00-2-2h.138" stroke="#79B8FF" stroke-linejoin="round"/>
                                            <path stroke="#2088FF" stroke-linejoin="round" d="M33 29h12M33 34h6M43 34h2"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Reviewer
                  
                </div>
                                <div class="text">Reviewed 33 pull requests</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="17.1356783919598 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-linecap="round" stroke-linejoin="round" stroke-width="2" fill="none" fill-rule="evenodd">
                                            <path stroke="#2088FF" d="M28.017 5v3M36.006 7.013l-1.987 2.024M20.021 7.011l1.988 2.011M28.806 30.23c-2.206-3.88-5.25-2.234-5.25-2.234 1.007 2.24 1.688 3.72 2.742 8.724.957 4.551 3.785 7.409 7.687 7.293l5.028 6.003M29.03 34.057L29 20.007m4.012 9.004V17.005m4.006 11.99l-.003-9.353"/>
                                            <path d="M18.993 50.038l4.045-5.993s1.03-.262 1.954-.984m-6.983.96c-4.474-.016-6.986-5.558-6.986-9.979 0-1.764-.439-4.997-1.997-8.004 0 0 3.268-1.24 5.747 3.6.904 1.768.458 5.267.642 5.388.185.121 1.336.554 2.637 2.01m4.955-18.92a976.92 976.92 0 010 5.91m-7.995-4.986l-.003 10.97M10.031 48.021l2.369-3.003" stroke="#79B8FF"/>
                                            <path d="M45.996 47.026l-1.99-2.497-1.993-2.5s2.995-1.485 2.995-6.46V24.033" stroke="#2088FF"/>
                                            <path d="M41 29v-6a2 2 0 114 0v2m-8-4v-4a2 2 0 114 0v7m-8-7v-2a2 2 0 114 0v2m-8 4v-2a2 2 0 114 0v2" stroke="#2088FF"/>
                                            <path d="M23 20v-2a2 2 0 013.043-1.707M19 19v-4a2 2 0 114 0v3m-8 3v-2a2 2 0 114 0v10" stroke="#79B8FF"/>
                                            <path d="M6.7 12c.316 1.122.572 1.372 1.71 1.678-1.136.314-1.39.566-1.7 1.69-.316-1.121-.572-1.372-1.71-1.678 1.135-.314 1.389-.567 1.7-1.69zm42 0c.316 1.122.572 1.372 1.71 1.678-1.136.314-1.39.566-1.7 1.69-.317-1.121-.573-1.372-1.71-1.679 1.135-.313 1.389-.566 1.7-1.689zM28.021 47.627c.317 1.122.573 1.372 1.71 1.678-1.135.314-1.389.566-1.699 1.69-.318-1.121-.573-1.372-1.71-1.679 1.134-.313 1.389-.566 1.699-1.689z" stroke="#2088FF"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Stargazer
                  
                </div>
                                <div class="text">Starred 23 repositories</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="12.525252525252526 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g transform="translate(4 4)" fill="none" fill-rule="evenodd">
                                            <path d="M20.065 47.122c.44-.525.58-1.448.58-1.889 0-2.204-1.483-3.967-3.633-4.187.447-1.537.58-2.64.397-3.31-.25-.92-.745-1.646-1.409-2.235m-5.97-7.157c.371-.254.911-.748 1.62-1.48a8.662 8.662 0 001.432-2.366M47 22h-7c-1.538 0-2.749-.357-4-1h-5c-1.789.001-3-1.3-3-2.955 0-1.656 1.211-3.04 3-3.045h2c.027-1.129.513-2.17 1-3m3.082 32.004C34.545 43.028 34.02 40.569 34 39v-1h-1c-2.603-.318-5-2.913-5-5.997S30.397 26 33 26h9c2.384 0 4.326 1.024 5.27 3" stroke="#79B8FF" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"/>
                                            <g transform="translate(36)" stroke="#2088FF" stroke-width="2">
                                                <path fill="#2088FF" stroke-linecap="round" stroke-linejoin="round" d="M5.395 5.352L6.009 4l.598 1.348L8 5.408l-1.067 1.12.425 1.47-1.356-.908-1.35.91.404-1.469L4 5.41z"/>
                                                <circle cx="6" cy="6" r="6"/>
                                            </g>
                                            <g transform="translate(0 31)" stroke="#2088FF" stroke-width="2">
                                                <circle cx="6" cy="6" r="6"/>
                                                <g stroke-linecap="round">
                                                    <path d="M6 4v4M4 6h4"/>
                                                </g>
                                            </g>
                                            <circle stroke="#2088FF" stroke-width="2" cx="10.5" cy="10.5" r="10.5"/>
                                            <g stroke-linecap="round">
                                                <path d="M32.01 1.37A23.96 23.96 0 0024 0c-.999 0-1.983.061-2.95.18M.32 20.072a24.21 24.21 0 00.015 7.948M12.42 45.025A23.892 23.892 0 0024 48c13.255 0 24-10.745 24-24 0-2.811-.483-5.51-1.371-8.016" stroke="#79B8FF" stroke-width="2"/>
                                                <path stroke="#2088FF" stroke-width="2" d="M8.999 7.151v5.865"/>
                                                <path d="M9 3a2 2 0 110 4 2 2 0 010-4zm0 10.8a2 2 0 11-.001 4 2 2 0 01.001-4z" stroke="#2088FF" stroke-width="1.8"/>
                                                <path d="M9.622 11.838c.138-.007.989.119 1.595-.05.607-.169 1.584-.539 1.829-1.337" stroke="#2088FF" stroke-width="2"/>
                                                <path d="M14.8 7.202a2 2 0 110 4 2 2 0 010-4z" stroke="#2088FF" stroke-width="1.8"/>
                                            </g>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Inspirationer
                  
                    <span class="gh">
                      ranked 829k out of 238m repositories
                    </span>
                  
                </div>
                                <div class="text">Maintaining a repository which has been forked 9 times</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="1.5577889447236182 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g fill="none" fill-rule="evenodd">
                                            <path d="M35 31a7 7 0 1114 0 7 7 0 01-14 0zm12-13a3 3 0 116 0 3 3 0 01-6 0zM33 49a3 3 0 116 0 3 3 0 01-6 0zM4 15a3 3 0 116 0 3 3 0 01-6 0zm37-8.5a2.5 2.5 0 115 0 2.5 2.5 0 01-5 0zM10 14l4.029-.576M19.008 26.016L21 19M29.019 34.001l5.967-1.948M36.997 46.003l2.977-8.02M46.05 24.031L48 21M28.787 18.012l7.248 8.009" stroke="#79B8FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M43.62 29.004c-1.157 0-1.437.676-1.62 1.173-.19-.498-.494-1.167-1.629-1.167-.909 0-1.355.777-1.371 1.632-.022 1.145 1.309 2.365 3 3.358 1.669-.983 3-2.23 3-3.358 0-.89-.54-1.638-1.38-1.638z" fill="#2088FF"/>
                                            <path stroke="#79B8FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" d="M48.043 15.003L45 9"/>
                                            <path d="M21 12a3 3 0 116 0 3 3 0 01-6 0zM27 12h3M18 12h3M21 43c-.267-1.727-1.973-3-4-3-2.08 0-3.787 1.318-4 3m4-9a3 3 0 100 6 3 3 0 000-6z" stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M17 30a9 9 0 110 18 9 9 0 110-18z" stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Follower
                  
                </div>
                                <div class="text">Following 3 users</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="1.5515515515515514 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g transform="translate(4 4)" fill="none" fill-rule="evenodd">
                                            <path d="M39 15h.96l4.038 3-.02-3H45a2 2 0 002-2V3a2 2 0 00-2-2H31a2 2 0 00-2 2v4.035" stroke="#79B8FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" d="M36 5.014l-3 3 3 3M40 5.014l3 3-3 3"/>
                                            <path d="M6 37a1 1 0 110 2 1 1 0 010-2m7 0a1 1 0 110 2 1 1 0 010-2m-2.448 1a1 1 0 11-2 0 1 1 0 012 0z" fill="#2088FF"/>
                                            <path d="M1.724 15.05A23.934 23.934 0 000 24c0 .686.029 1.366.085 2.037m19.92 21.632c1.3.218 2.634.331 3.995.331a23.92 23.92 0 009.036-1.76m13.207-13.21A23.932 23.932 0 0048 24c0-1.363-.114-2.7-.332-4M25.064.022a23.932 23.932 0 00-10.073 1.725" stroke="#79B8FF" stroke-width="2" stroke-linecap="round"/>
                                            <path d="M19 42.062V43a2 2 0 01-2 2H9.04l-4.038 3 .02-3H3a2 2 0 01-2-2V33a2 2 0 012-2h4.045" stroke="#79B8FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M6 0a6 6 0 110 12A6 6 0 016 0z" stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path stroke="#2088FF" stroke-width="2" stroke-linecap="round" d="M6 3v6M3 6h6"/>
                                            <path d="M42 36a6 6 0 110 12 6 6 0 010-12z" stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path stroke="#2088FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" d="M44.338 40.663l-3.336 3.331-1.692-1.686M31 31c-.716-2.865-3.578-5-7-5-3.423 0-6.287 2.14-7 5"/>
                                            <path d="M24 16a5 5 0 110 10 5 5 0 010-10z" stroke="#2088FF" stroke-width="2" stroke-linecap="round"/>
                                            <circle stroke="#2088FF" stroke-width="2" cx="24" cy="24" r="14"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Maintainer
                  
                    <span class="gh">
                      ranked 1.16m out of 238m repositories
                    </span>
                  
                </div>
                                <div class="text">Maintaining a repository with 11 stars</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="0 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-width="2" fill="none" fill-rule="evenodd">
                                            <path d="M29 16V8.867C29 7.705 29.627 7 30.692 7h18.616C50.373 7 51 7.705 51 8.867v38.266C51 48.295 50.373 49 49.308 49H30.692C29.627 49 29 48.295 29 47.133V39m-4-23V9c0-1.253-.737-2-2-2H7c-1.263 0-2 .747-2 2v34c0 1.253.737 2 2 2h16c1.263 0 2-.747 2-2v-4" stroke="#79B8FF" stroke-linecap="round"/>
                                            <path stroke="#79B8FF" d="M51.557 12.005h-22M5 12.005h21"/>
                                            <path d="M14 33V22c0-1.246.649-2 1.73-2h28.54c1.081 0 1.73.754 1.73 2v11c0 1.246-.649 2-1.73 2H15.73c-1.081 0-1.73-.754-1.73-2z" stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M19 29v-3c0-.508.492-1 1-1h3c.508 0 1 .492 1 1v3c0 .508-.492 1-1 1h-3c-.508-.082-1-.492-1-1z" stroke="#2088FF"/>
                                            <path stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round" d="M28.996 27.998h12M9.065 20.04a7.062 7.062 0 00-.023 1.728m.775 2.517c.264.495.584.954.954 1.369"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Manager
                  
                </div>
                                <div class="text">Created 1 user project</div>
                            </div>
                        </div>
                        <div class="achievement c largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="0 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g stroke-width="2" fill="none" fill-rule="evenodd">
                                            <path d="M20 48.875v-12.75c0-1.33.773-2.131 2.385-2.125h26.23c1.612-.006 2.385.795 2.385 2.125v12.75C51 50.198 50.227 51 48.615 51h-26.23C20.773 51 20 50.198 20 48.875zM37 40.505h9M37 44.492h6" stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path stroke="#79B8FF" stroke-linecap="round" stroke-linejoin="round" d="M14 30h-4M16 35h-3M47 10H5M42 15H24M19 15h-9M16 25h-3M42 20h-2M42 20h-2M42 25h-2M16 20h-3"/>
                                            <path stroke="#2088FF" stroke-linecap="round" stroke-linejoin="round" d="M31.974 25H24"/>
                                            <path d="M22 20h12a2 2 0 012 2v6a2 2 0 01-2 2H22a2 2 0 01-2-2v-6a2 2 0 012-2z" stroke="#2088FF"/>
                                            <path d="M5 33V7a2 2 0 012-2h38a2 2 0 012 2v23" stroke="#79B8FF" stroke-linecap="round"/>
                                            <path d="M5 30v8c0 1.105.892 2 1.993 2H16" stroke="#79B8FF" stroke-linecap="round"/>
                                            <g stroke="#2088FF" stroke-linecap="round">
                                                <path d="M26.432 37.933v7.07M26.432 37.933v9.07M24.432 40.433h7.07M24.432 40.433h8.07M24.432 44.433h7.07M24.432 44.433h8.07M30.432 37.933v9.07"/>
                                            </g>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Scripter
                  
                </div>
                                <div class="text">Published 1 gist</div>
                            </div>
                        </div>
                        <div class="achievement secret largeable-width-half">
                            <div class="icon">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60" height="44" width="44">
                                    <defs>
                                        <mask id="mask">
                                            <circle class="gauge-base" r="25" cx="28" cy="28" fill="white"/>
                                        </mask>
                                    </defs>
                                    <svg xmlns="http://www.w3.org/2000/svg" class="gauge info">
                                        <circle class="gauge-base" r="25" cx="28" cy="28"/>
                                        <circle class="gauge-arc" transform="rotate(-90 28 28)" r="25" cx="28" cy="28" stroke-dasharray="155 155"/>
                                    </svg>
                                    <svg xmlns="http://www.w3.org/2000/svg" mask="url(#mask)">
                                        <g transform="translate(4 5)" stroke-width="2" fill="none" fill-rule="evenodd">
                                            <g stroke-linecap="round" stroke-linejoin="round">
                                                <path stroke="#FF48BD" d="M26.478 22l.696 2.087 3.478.696v2.782l-3.478 1.392-.696 1.39 1.392 3.48-1.392 1.39L23 33.827l-1.391.695L20.217 38h-2.782l-1.392-3.478-1.39-.696-3.48 1.391-1.39-1.39 1.39-3.48-.695-1.39L7 27.565v-2.782l3.478-1.392.696-1.391-1.391-3.478 1.39-1.392 3.48 1.392 1.39-.696 1.392-3.478h2.782l1.392 3.478 1.391.696 3.478-1.392 1.392 1.392z"/>
                                                <path stroke="#FF92D8" d="M24.779 12.899l-1.475-2.212 1.475-1.475 2.95 1.475 1.474-.738.737-2.934h2.212l.737 2.934 1.475.738 2.95-1.475 1.474 1.475-1.475 2.949.738 1.475 2.949.737v2.212l-2.95.737-.737 1.475 1.475 2.949-1.475 1.475-2.949-1.475"/>
                                            </g>
                                            <path stroke="#FF48BD" stroke-linecap="round" d="M5.932 5.546l7.082 6.931"/>
                                            <path stroke="#FF92D8" stroke-linecap="round" d="M32.959 31.99l8.728 8.532"/>
                                            <circle stroke="#FF92D8" cx="44" cy="43" r="3"/>
                                            <circle stroke="#FF48BD" cx="13" cy="2" r="2"/>
                                            <circle stroke="#FF92D8" cx="35" cy="44" r="2"/>
                                            <circle stroke="#FF92D8" cx="3" cy="12" r="2"/>
                                            <circle stroke="#FF48BD" cx="45" cy="34" r="2"/>
                                            <path d="M3.832 0a3 3 0 110 6 3 3 0 010-6zM8.04 10.613l2.1-.613M10.334 9.758l1.914-5.669" stroke="#FF48BD" stroke-linecap="round"/>
                                            <path stroke="#FF92D8" stroke-linecap="round" d="M40.026 35.91l-2.025.591M35.695 41.965l1.843-5.326"/>
                                            <path d="M16 2h23.038a6 6 0 016 6v24.033" stroke="#FF48BD" stroke-linecap="round"/>
                                            <path d="M32.038 44.033H9a6 6 0 01-6-6V14" stroke="#FF92D8" stroke-linecap="round"/>
                                            <path d="M17.533 22.154l5.113 3.22a1 1 0 01-.006 1.697l-5.113 3.17a1 1 0 01-1.527-.85V23a1 1 0 011.533-.846zm11.58-7.134v-.504a1 1 0 011.53-.85l3.845 2.397a1 1 0 01-.006 1.701l-3.846 2.358" stroke="#FF48BD" stroke-linecap="round" stroke-linejoin="round"/>
                                        </g>
                                    </svg>
                                </svg>
                            </div>
                            <div class="info">
                                <div class="title">
                  Automater
                  
                </div>
                                <div class="text">Use GitHub Actions to automate profile updates</div>
                            </div>
                        </div>
                    </section>
                </div>
            </section>
            <footer>
                <span>These metrics include private contributions</span>
                <span>Last updated Tue, 13 Jul 2021 22:20:24 (timezone Europe/Bratislava) with lowlighter/metrics@3.10.0</span>
            </footer>
            <div id="metrics-end"></div>
        </div>
    </foreignObject>
</svg>
