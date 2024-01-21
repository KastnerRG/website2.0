# website2.0
Kastner Research Group Jekyll Website

## Developer Get Started
1. Follow the instructions at https://jekyllrb.com/docs/installation/ to install the Jekyll generator on your machine.
2. Run `bundle exec jekyll serve --livereload` in this repository root to deploy a live server to http://localhost:4000

## Adding Publications
1. Open [_bibliography/publications.bib](_bibliography/publications.bib) in [JabRef](https://www.jabref.org/).
2. Add the new publication using the correct classification
    1. Books should use `@Book`
    2. PhD theses should `@PhdThesis` with `type` set to `PhD Thesis`
    3. MS theses should use `@MastersThesis` with `type` set to `MS Thesis`
    4. Patents should use `@Patent` with `number` set to the full US Patent number (e.g. `US0123456789`)
    5. Book chapters should use `@InBook`
    6. Conference papers should use `@InProceedings`
    7. Journal articles should use `@Article`
3. Commit the updated `.bib` file and push to `main`