# OrigamiJumper

This repository is for the ICRA 2022 paper: "Printable Origami Bistable Structures for Foldable Jumpers".

The repository includes:

- Grasshopper designing file for waterbomb (SW), split-fold waterbomb (SFWB)
- Pattern to be used with laser cutter to make the origami SW/SFWB structures
- Some animation on the transition of the SW and SFWB structure between bi-stable states

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/15y4ZFg5i5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

# How to use Grasshopper files?

**Software Requirements:**

- [Rhinoceros 7.0 (including Grasshopper plugin)](https://www.rhino3d.com)
- [Kangaroo 2](https://www.food4rhino.com/en/app/kangaroo-physics)

We assume that you have Rhinoceros/Grasshopper and Kangaroo 2 installed. After openning the .gh file, find the `Reset` button inside the design file and press it, you will see the SW/SFWB on the Rhinoceros screen.

![Grasshopper Reset Button](/docs/assets/images/grasshopper_resetbutton.png)

You can play with other parameters such as:

- `N.Num` : degree of the SW/SFWB structure. It specifies the number of mountain folds OR valley folds (for SW, `N.Num = 10` means that there are 10 mountain folds and 10 valley folds)
- `Folding Angle`: folding angle at the vortex of the waterbomb structure (angle **θ** in paper)
- `Vertical Load`: the normal load applied on the vortext of the waterbomb structure
- `Mountain Fold Strength`: the stiffness of mountain fold (valley folds should have different value, but for the sake of simplicity, we will assume that a valley fold and a mountain fold both have a same value of stiffness)

# Laser cutting patterns

We include ready made SW and SFWB patterns for laser cutting. We use Takeo Tant paper as the material of origami structure (see paper for more detail on the material)

# Citation

T. D. Ta*, Z. Chang*, K. Narumi, T. Umedachi, and Y. Kawahara, “**Printable Kirigami Bistable Structures for Foldable Jumping Robots,**” 2022 IEEE International Conference on Robotics and Automation (ICRA), 2022, To Appear. (* Co-first authors)
