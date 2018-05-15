# Code CSS

```css
strong, b {
  color: rgba(255, 255, 255, 0.875);
  font-weight: 400; }

em, i {
  font-style: italic; }

p {
  margin: 0 0 1.5rem 0; }
  body.is-ie p {
    width: 100%; }

h1, h2, h3, h4, h5, h6 {
  color: rgba(255, 255, 255, 0.875);
  font-family: "Julius Sans One", Helvetica, sans-serif;
  font-weight: 700;
  line-height: 1.3;
  margin: 0 0 0.75rem 0;
  letter-spacing: -0.03em; }
  h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
    color: inherit;
    text-decoration: none; }

h3, h4, h5, h6 {
  font-weight: 400; }

h1.major, h2.major, h3.major {
  position: relative; }
  h1.major:after, h2.major:after, h3.major:after {
    content: '';
    position: absolute;
    left: 0;
    width: 3.5rem;
    height: 0.1rem;
    background-color: rgba(255, 255, 255, 0.25); }

h1 {
  font-size: 3rem;
  line-height: 1.2; }
  h1.major {
    margin: 0 0 2.625rem 0; }
    h1.major:after {
      bottom: -1.325rem; }

h2 {
  font-size: 1.75rem;
  line-height: 1.2; }
  h2.major {
    margin: 0 0 1.9875rem 0; }
    h2.major:after {
      bottom: -1.2rem; }

h3 {
  font-size: 1.325rem; }
  h3.major {
    margin: 0 0 1.875rem 0; }
    h3.major:after {
      bottom: -0.75rem; }

h4 {
  font-size: 1rem; }

h5 {
  font-size: 0.9rem; }

h6 {
  font-size: 0.7rem; }

sub {
  font-size: 0.8rem;
  position: relative;
  top: 0.5rem; }

sup {
  font-size: 0.8rem;
  position: relative;
  top: -0.5rem; }

blockquote {
  border-left: solid 0.25rem rgba(255, 255, 255, 0.25);
  font-style: italic;
  margin: 0 0 1.5rem 0;
  padding: 0.375rem 0 0.375rem 1.5rem; }

code {
  background: rgba(255, 255, 255, 0.075);
  border-radius: 0.25rem;
  font-family: "monofur", monospace;
  font-size: 1.1rem;
  margin: 0 0.25rem;
  padding: 0.11rem 0.25rem; }

pre {
  -webkit-overflow-scrolling: touch;
  font-family: "monofur", monospace;
  font-size: 0.8rem;
  margin: 0 0 1.5rem 0;
  white-space: pre-wrap; }
  pre code {
    display: block;
    line-height: 1.625;
    padding: 1rem 1.5rem;
    overflow-x: auto;
    margin: 0; }

hr {
  border: 0;
  border-bottom: solid 2px rgba(255, 255, 255, 0.25);
  margin: 1.875rem 0; }

.align-left {
  text-align: left; }

.align-center {
  text-align: center; }

.align-right {
  text-align: right; }
