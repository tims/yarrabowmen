# Yarra Bowmen

The official website for Yarra Bowmen Inc., one of Victoria’s oldest target archery clubs. Established in 1963 and situated in Bulleen Park, the club serves the CBD and eastern suburbs of Melbourne.

## About the Club

Yarra Bowmen is registered with [Archery Victoria](http://archeryvic.org.au/) and offers:
- A 90m range capable of fitting 30+ targets.
- All-week shooting during daylight hours for members.
- Beginners courses for individuals aged 10 and older.
- A large clubhouse and storage facilities.

The club is run entirely by volunteers and operates on grounds leased from the Manningham City Council.

## Getting Started

### Prerequisites

To run this project locally, you need to have [Hugo](https://gohugo.io/) installed.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yarrabowmen/yarrabowmen.github.io.git
   cd yarrabowmen
   ```

2. Run the development server:
   ```bash
   ./preview.sh
   ```
   This script runs `hugo server --buildDrafts --disableFastRender`.

3. Open your browser and navigate to `http://localhost:1313`.

## Project Structure

- `content/`: Markdown files for the website pages (Home, Membership, Visitors, etc.).
- `assets/images/`: Site images and logos.
- `layouts/`: Custom HTML templates and partials.
- `hugo.yaml`: Site configuration, menus, and metadata.
- `.github/workflows/hugo.yaml`: GitHub Actions workflow for automated deployment.

## Deployment

The site is automatically built and deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the main branch.

## Contact Information

- **Address:** PO BOX 71, BULLEEN VIC 3105
- **Email:** yarrabowmeninc@gmail.com
- **Registration:** Incorporated Association Registration Number: A0017284L

© 2025 Yarra Bowmen
