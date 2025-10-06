# Breadpans

These breadpans are designed to screw into a COM-8 CS:L frame using existing screw holes. It may be necessary to 
make some countersink holes so that the screws do not interfere with the frame but otherwise they should not
require modification to install.

## Other Parts

- 1x [Dynamixel XL-320](https://emanual.robotis.com/docs/en/dxl/x/xl320/)
- 2x [3mm x 300mm Steel Rod](https://www.amazon.ca/dp/B0BLXQXNNZ)
- 3x [5mm ID x 11mm OD x 5mm Thick Bearings](https://www.amazon.ca/dp/B0CH2XL42Q?th=1)
- 2x [2mm ID x 7mm OD x 3mm Thick Bearings](https://www.amazon.ca/dp/B0CH2ZBCNW?th=1)
- [M3 Heat Set Inserts](https://www.mcmaster.com/94180A331/)
- M3 Nuts
- M3 Screws (likely several lengths, you'll need flat head ones for the `Bottom Bearing Holder`)

> Note: I've designed with metric hardware in mind. It may be possible to use 4-40 hardware in place of the metric hardware.

## Printing Details

I printed this in PLA / PETG. It would probably be better in something more rigid but I haven't tried anything more advanced.

The doors should be printed such that the arm portion is 100% infill. This can be done with print modifiers. They are also designed to print at 0.2mm layer height if my memory is correct. As this uses heat set inserts I believe I used a strength profile in Bambu studio (which gives 6 walls)

The magnets for the doors are embedded into the print. This can be acheived by pausing the prints at the layers which cover the top of the cavities and inserting magnets.

There are also some "retention" magnets embedded into the main body at the top and bottom in small tabs.

I glued the three hinge parts together using E6000. Before doing so I placed rods into the two outer verticals.

## General Assembly Notes:

- The 7mm OD bearings are used in the push rod. M3 screws are used through these to connect to heat set inserts. I used a bit of thread locker to keep them in place.

- The 11mm OD bearings go into the bottom portion, the upper portion and the `Bottom Bearing Holder` which is then affixed using screws

- The vertical holes on the side are to allow for a linear bearing (block & slide). I haven't implemented anyhting with this yet though so can't speak to how well it works.

- The two halves of the main body are connected using machine screws and nuts.

- Heat set inserts are used in the servo horn, the `Bottom Bearing Holder`, and a number of places in the outer Frame. Specifically they are used for the servo cover attachment points as well the positions on the top and bottom where the device will connect to the frame.

