# OrigamiJumper

This repository is for the ICRA 2022 paper: "Printable Origami Bistable Structures for Foldable Jumpers".

The repository includes:

- Grasshopper designing file for waterbomb (SW), split-fold waterbomb (SFWB)
- Pattern to be used with laser cutter to make the origami SW/SFWB structures
- Some animation on the transition of the SW and SFWB structure between bi-stable states

# How to use Grasshopper files?

**Software Requirements:**

- [Rhinoceros 7.0 (including Grasshopper plugin)](https://www.rhino3d.com)
- [Kangaroo 2](https://www.food4rhino.com/en/app/kangaroo-physics)

We assume that you have Rhinoceros/Grasshopper and Kangaroo 2 installed. After openning the .gh file, find the `Reset` button inside the design file and press it, you will see the SW/SFWB on the Rhinoceros screen.

![Screen Shot 2022-05-24 at 22.36.05.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a8a1abed-a659-4f82-8849-3c4db099664b/Screen_Shot_2022-05-24_at_22.36.05.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220525%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220525T025035Z&X-Amz-Expires=86400&X-Amz-Signature=a02e6ae178d2dc1d4d4f2b6339a49d271dd7a714546306e032e819393271edc3&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Screen%2520Shot%25202022-05-24%2520at%252022.36.05.png%22&x-id=GetObject)

You can play with other parameters such as:

- `N.Num` : degree of the SW/SFW structure. It specifies the number of mountain folds OR valley folds (for SW, `N.Num = 10` means that there are 10 mountain folds and 10 valley folds)
- `Folding Angle`: folding angle at the vortex of the waterbomb structure (angle **θ** in paper)
- `Vertical Load`: the normal load applied on the vortext of the waterbomb structure
- `Mountain Fold Strength`: the stiffness of mountain fold (valley folds should have different value, but for the sake of simplicity, we will assume that a valley fold and a mountain fold both have a same value of stiffness)

# Laser cutting patterns

File `LaserCut_ICRA2022.dxf` includes ready made SW and SFWB patterns for laser cutting. We use Takeo Tant paper as the material of origami structure (see paper for more detail on the material)

# Citation

**T. D. Ta***, Z. Chang*, K. Narumi, T. Umedachi, and Y. Kawahara, “**Printable Kirigami Bistable Structures for Foldable Jumping Robots,**” 2022 IEEE International Conference on Robotics and Automation (ICRA), 2022, To Appear. (* Co-first authors)