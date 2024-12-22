# PiRTO II
PiRTO II if a flash multicart for the Mattel Intellivision based on the Raspberry Pico.

![Board](https://raw.githubusercontent.com/SukkoPera/PiRTOII/original_pico/img/render-top.png)

## Summary
This is my variation on [Andrea Ottaviani's PiRTO II](https://github.com/aotta/PiRTOII) flash multicart for the Mattel Intellivision.

My original goal was to adapt it in order to use original Pico boards, of which I had plenty. While studying the project I decided to introduce proper level shifting and a MicroSD card slot (since the original Pico has less flash space than the purple clones used in the original project). All of this eventually made the project very similar to Andrea's [first version of the cart](https://github.com/aotta/PiRTO), of which I was unaware of the time, but it uses through-hole components and one less chip.

## Usage
The Pico **MUST** be flashed with the firmware that is available on this page. Do **NOT** use the firmware from the original project, I will try to incorporate any upstream changes.

Note that **support for the SD card has NOT yet been implemented**.

For all the rest, please refer to [the original project](https://github.com/aotta/PiRTOII) or to the [AtariAge forum](https://forums.atariage.com/forum/125-intellivision-aquarius/).

## Assembly
This board was designed **for the original Raspberry Pico board**, so either use that or a clone that has the same pinout. It's your responsibility to ascertain that.

U2/3/4 **MUST** be 74LVC245. Do **NOT** get these from China, as they will likely be HC chips with just different (incorrect) markings. Rather get them from Mouser, Digikey, RS, etc.

Other BJTs will probably work for Q1, just make sure they have the same pinout.

JP1/2/3/4 are experimental jumpers and **MUST** be closed for the moment.

## Releases
If you want to get this board produced, you are recommended to get [the latest release](https://github.com/SukkoPera/PiRTOII/releases) rather than the current git version, as the latter might be under development and is not guaranteed to be working.

Every release is accompanied by its Bill Of Materials (BOM) file and any relevant notes about it, which you are recommended to read carefully.

## License
Despite [an effort to clear things up](https://github.com/aotta/PiRTOII/issues/2), the license status of Andrea's original board is unclear, so I don't really know what to do. I don't want to add or remove any limitations compared to the original project, so please get in touch with him before you use this project in any way.

Still, let me point out that this PiRTOII variation is provided to you ‘as is’ and without any express or implied warranties whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties of merchantability, fitness for a particular purpose or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.

## Support the Project
If you want to get some boards manufactured, you can get them from PCBWay through this link:

[![PCB from PCBWay](https://www.pcbway.com/project/img/images/frompcbway.png)](https://www.pcbway.com/project/shareproject/PiRTOII_Flash_multicart_for_the_Mattel_Intellivision_Original_Pico_Version_95662f2b.html)

You get my gratitude and cheap, professionally-made and good quality PCBs, I get some credit that will help with this and [other projects](https://www.pcbway.com/project/member/?bmbno=72D33927-5EF6-42). You won't even have to worry about the various PCB options, it's all pre-configured for you!

Also, if you still have to register, [you can use this link](https://pcbway.com/g/Nz7XZs) to get some bonus initial credit (and yield me some more).

You can also buy me a coffee if you want, all the money collected this way will actually go to charity:

<a href='https://ko-fi.com/L3L0U18L' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>


## Thanks
Of course, I would like to thank Andrea for his original project.
