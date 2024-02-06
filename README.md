# What This Is

A while ago, I happed upon a really cool tech essay about our digital diet. In the end, it had a neat little way of numbering the points / headings, whereby the preceding number (`0` for most of the list) would scroll along with the viewer, while the following number (`1` through `9`) would only scroll within the section which the heading framed.

It was a cool feature, but it was implemented in a seriously heavy-handed with, with a large amount of JS (which, to be fair, was necessary for the rest of the essay, since it's animation-heavy) augmenting the CSS. I wanted to see if this were implementable in pure CSS. This is my attempt at it.

# Why This Exists

I'm a strong believer in the principle of least power when it comes to telling a story. This is relevant to code and design because both only exist in service of a greater goal: to persuade, to impress, to enchant, to promote, to suggest...

Using least-powerful tools to accomplish a goal means efficiency: it means spending resources with as little waste as possible. Baseline CSS is magnitudes-of-order less-powerful a presentation tool than, say, React; but if it can accomplish the same goal without invoking complex developmental and building processes, simply by relying on the browser's expected capacity, it may be a better tool for the job.

The less the power, the less reasoning is required to make sense of the system when viewed by a new eye. Simple things are, by their nature, simple. This makes least-powerful systems easier to teach and easier to learn, making it a more-potent investment into one's skillset.

Building a system of least power is an intellectual challenge, which is something I enjoy about working with both code and design.

# Is This Immediately Usable?

No, but you can learn how it works and copy the principle. A lot of the CSS is presentational; the important part is the CSS Grid-based "tracks" upon which the numbers move.

(When in use with React or another popular framework, it could be abstracted to render the new tracks for each digit of the heading number, though if you need more than two, perhaps it's wise to reassess the base assumptions of the design.)

# License

MIT
