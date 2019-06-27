# UI Buttons

**Density-independent pixel \(dp\)**  
A virtual pixel unit that you should use when defining UI layout, to express layout dimensions or position in a density-independent way. The density-independent pixel is equivalent to one physical pixel on a 160 dpi screen, which is the baseline density assumed by the system for a "medium" density screen. At runtime, the system transparently handles any scaling of the dp units, as necessary, based on the actual density of the screen in use. The conversion of dp units to screen pixels is simple: `px = dp * (dpi / 160)`. For example, on a 240 dpi screen, 1 dp equals 1.5 physical pixels. You should always use dp units when defining your application's UI, to ensure proper display of your UI on screens with different densities.

Bron: [https://stackoverflow.com/questions/2025282/what-is-the-difference-between-px-dip-dp-and-sp](https://stackoverflow.com/questions/2025282/what-is-the-difference-between-px-dip-dp-and-sp)



