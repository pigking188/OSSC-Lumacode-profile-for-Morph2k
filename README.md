# OSSC-Lumacode-profile-for-Morph2k

These are a set of profiles I designed for a very specific purpose: playing a Lumacode modded NES on the Morph2k, using the OSSC as an intermediary.

The input chain looks like this:

`Lumacode Modded NES --> OSSC --> HDMI to VGA Cable --> Morph2k`

This should, in theory, result in an incredibly sharp and accurate sampling of original NES hardware, with the benefit of much more control over the way the final image is displayed.

## What you'll need:

* A Lumacode modded NES console
* An OSSC running firmware v1.21 or higher
* This HDMI to VGA cable: https://www.amazon.com/dp/B07CTK4TH4
* A Morph2k with accompanying VGA2SCART adapter.

The above HDMI to VGA adapter was taken from RetroRGB's list of verified zero-lag adapters, and should in theory add zero input lag to your chain.
https://www.amazon.com/shop/retrorgb/list/IP72N6BL06SV?ccs_id=daceb646-815d-4587-a1ed-74e4925c2c1d

## How to use:

With all the required devices connected as described above, download profXX.bin, rename it to an unused profile on your OSSC, (prof01.bin, prof02.bin, etc.), and place it on your OSSC's SD card. Power on your NES, navigate your OSSC to the correct input, and load the profile. Download NES Lumacode OSSC VGA 240p.ini, and place it in the profiles section of your Morph 2k's SD card. Set the Morph 2k to VGA input, and load the profile.

By default, the Morph 2k profile is configured for 1440p output. It's set to fill the screen with a 6x horizontal integer scale at an accurate 4:3 aspect ratio, and uses sharp horizontal interpolation to ensure smooth scrolling and even horizontal pixel sizing. These can all be tweaked to match your personal display preferences: simply make your changes and resave the profile.

## Results:

Although this input chain does technically introduce the potential for analog noise into what could be, hypothetically, an entirely digital environment, I feel like the results that can be achieved are excellent. The underlying NES pixels are sampled in a way that are, perceptibly, pixel perfect, and you gain significantly more control over how the final image is scaled, processed, and displayed, than relying entirely on the OSSC to do the final image processing.

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Mario%20Composite.png" alt="Direct composite input on the Morph 2k">
      <br>
      <sub>Direct composite input on the Morph 2k</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Mario%20Lumacode.png" alt="Lumacode on the Morph2k via the aforementioned profile">
      <br>
      <sub>Lumacode on the Morph2k via the aforementioned profile</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Mario.png" alt="Perfect pixel sampling">
      <br>
      <sub>Perfect pixel sampling</sub>
    </td>
  </tr>
</table>

<br>

Comparison photos are using FirebrandX's "Smooth" NES palette, but any NES color palette can be configured via the OSSC.

<br>

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Mega%20Man%20Composite.png" alt="Direct composite input on the Morph 2k">
      <br>
      <sub>Direct composite input on the Morph 2k</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Mega%20Man%20Lumacode.png" alt="Lumacode on the Morph2k via the aforementioned profile">
      <br>
      <sub>Lumacode on the Morph2k via the aforementioned profile</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Mega%20Man.png" alt="Perfect pixel sampling">
      <br>
      <sub>Perfect pixel sampling</sub>
    </td>
  </tr>
</table>

<br>

Please note: Comparison photos were taken at a 4:3 aspect ratio with interpolation set to off, for the purpose of displaying perfectly sharp pixel edges. This results in uneven pixel sizing. The actual profile has interpolation set to on, which corrects this.

<br>

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Zelda%20Composite.png" alt="Direct composite input on the Morph 2k">
      <br>
      <sub>Direct composite input on the Morph 2k</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Zelda%20Lumacode.png" alt="Lumacode on the Morph2k via the aforementioned profile">
      <br>
      <sub>Lumacode on the Morph2k via the aforementioned profile</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://github.com/pigking188/OSSC-Lumacode-profile-for-Morph2k/blob/main/Morph2k%20OSSC%20Lumacode%20Screenshots/Zelda.png" alt="Perfect pixel sampling">
      <br>
      <sub>Perfect pixel sampling</sub>
    </td>
  </tr>
</table>
