# My Class 12 Aerospace Engineering Portfolio

Hey everyone! I just finished my high school board exams in India and I am trying to get into a good Aerospace Engineering program. This is my Aerospace Engineering practice work, alongside my Electrical Engineering portfolio (see my other repository).

I passed 12th this year but couldn't afford college right away due to financial reasons, so I took a drop year. I decided to use that year to build something real instead of just waiting, so I taught myself NASA's free tool, OpenVSP, and built a simple aircraft model.

## What I Built: MiG-21 3D Model

I chose the MiG-21 because of its thin, slender body shape. A lot of modern fighter aircraft still share similar design qualities, so I thought modeling an older aircraft with that shape would help me understand ideas that are still relevant today. It's also a well-known Russian aircraft with a long history connected to India, which made it feel like a meaningful choice.

I kept the model simple on purpose — just fuselage, wings, and tail — because I'm a beginner and didn't want to fake more skill than I actually have.

- Fuselage length: 14.7 m, diameter: 1.24 m
- Wingspan: 7.15 m total, sweep angle: 57°
- Tail height: 2.1 m, sweep angle: 60°

The Result: You can view my completed 3D model layout named `figure 1.1 plane_diagram.png` right here in my repository.

## Testing It: Airflow Simulation

I ran the built-in VSPAERO simulation at Mach 1.5 and a 2° angle of attack, to see how air would move around the model. The result graph came out slightly jagged and not perfectly smooth — I'm including it as it is, mistakes included, because I think that's more honest than hiding it.

Lift happens because of pressure difference over the wing (Bernoulli's principle). I used AI and YouTube to understand how to read the graph properly.

The Result: You can view my lift distribution graph named `figure 1.2 flow_chart.png` right here in my repository.

## What Was Me, and What Wasn't

The software did the actual math. What I did myself: found the real MiG-21 dimensions, entered them correctly, fixed errors when the model looked wrong, chose the mesh settings, and understood what the final graph meant using basic physics.

## What's Next

This is a small project, but I built it from zero knowledge of this software. I want to keep doing this kind of work at a real university, with real labs and real teachers, instead of alone on YouTube.
