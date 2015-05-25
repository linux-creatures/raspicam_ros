<h1>Camera</h1>
<table>
<thead>
<tr>
<th></th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td>Net price</td>
<td>25 $</td>
</tr>
<tr>
<td>Size</td>
<td>around 25 x 20 x 9 mm</td>
</tr>
<tr>
<td>Weight</td>
<td>3 g</td>
</tr>
<tr>
<td>Still resolution</td>
<td>5 Megapixels</td>
</tr>
<tr>
<td>Video modes</td>
<td>1080p30, 720p60 and 640x480p60/90</td>
</tr>
<tr>
<td>Linux integration</td>
<td>V4L2 driver available</td>
</tr>
<tr>
<td>C programming API</td>
<td>OpenMAX IL and others available</td>
</tr>
<tr>
<td>Sensor</td>
<td>OmniVision OV5647</td>
</tr>
<tr>
<td>Sensor resolution</td>
<td>2592 x 1944 pixels</td>
</tr>
<tr>
<td>Sensor image area</td>
<td>3.76 x 2.74 mm</td>
</tr>
<tr>
<td>Pixel size</td>
<td>1.4 µm x 1.4 µm</td>
</tr>
<tr>
<td>Optical size</td>
<td>1/4&quot;</td>
</tr>
<tr>
<td>Full-frame SLR lens equivalent</td>
<td>35 mm</td>
</tr>
<tr>
<td>S/N ratio</td>
<td>36 dB</td>
</tr>
<tr>
<td>Dynamic range</td>
<td>67 dB @ 8x gain</td>
</tr>
<tr>
<td>Densitivity</td>
<td>680 mV/lux-sec</td>
</tr>
<tr>
<td>Dark current</td>
<td>16 mV/sec @ 60 C</td>
</tr>
<tr>
<td>Well capacity</td>
<td>4.3 Ke-</td>
</tr>
<tr>
<td>Fixed Focus</td>
<td>1 m to infinity</td>
</tr>
<tr>
<td>Focal length</td>
<td>3.60 mm +/- 0.01</td>
</tr>
<tr>
<td>Horizontal field of view</td>
<td>53.50  +/- 0.13 degrees</td>
</tr>
<tr>
<td>Vertical field of view</td>
<td>41.41 +/- 0.11 degress</td>
</tr>
<tr>
<td>Focal ratio (F-Stop)</td>
<td>2.9</td>
</tr>
</tbody>
</table>
<h2>Hardware Features</h2>
<table>
<thead>
<tr>
<th>Available</th>
<th>Implemented</th>
</tr>
</thead>
<tbody>
<tr>
<td>Chief Ray Angle Correction</td>
<td>Yes</td>
</tr>
<tr>
<td>Global and rolling shutter</td>
<td>Rolling shutter</td>
</tr>
<tr>
<td>Automatic exposure control (AEC)</td>
<td>No - done by ISP instead</td>
</tr>
<tr>
<td>Automatic white balance (AWB)</td>
<td>No - done by ISP instead</td>
</tr>
<tr>
<td>Automatic black level calibration (ABLC)</td>
<td>No - done by ISP instead</td>
</tr>
<tr>
<td>Automatic 50/60 Hz luminance detection</td>
<td>No - done by ISP instead</td>
</tr>
<tr>
<td>Frame rate up to 120 fps</td>
<td>max 90fps. Limitations on frame size for the higher frame rates (VGA only for above 47fps)</td>
</tr>
<tr>
<td>AEC/AGC 16-zone size/position/weight control</td>
<td>No - done by ISP instead</td>
</tr>
<tr>
<td>Mirror and flip</td>
<td>Yes</td>
</tr>
<tr>
<td>Cropping</td>
<td>No - done by ISP instead (except 1080p mode)</td>
</tr>
<tr>
<td>Lens correction</td>
<td>No - done by ISP instead</td>
</tr>
<tr>
<td>Defective pixel canceling</td>
<td>No - done by ISP instead</td>
</tr>
<tr>
<td>10-bit RAW RGB data</td>
<td>Yes , format conversions available via GPU</td>
</tr>
<tr>
<td>Support for LED and flash strobe mode</td>
<td>LED flash</td>
</tr>
<tr>
<td>Support for internal and external frame synchronization for frame exposure mode</td>
<td>No</td>
</tr>
<tr>
<td>Support for 2x2 binning for better SNR in low light conditions</td>
<td>Anything output res below 1296x976 will use the 2x2 binned mode</td>
</tr>
<tr>
<td>Support for horizontal and vertical sub-sampling</td>
<td>Yes , via Binning and skipping</td>
</tr>
<tr>
<td>On-chip phase lock loop (PLL)</td>
<td>Yes</td>
</tr>
<tr>
<td>Standard serial SCCB interface</td>
<td>Yes</td>
</tr>
<tr>
<td>Digital video port (DVP) parallel output interface</td>
<td>No</td>
</tr>
<tr>
<td>MIPI interface (two lanes)</td>
<td>Yes</td>
</tr>
<tr>
<td>32 bytes of embedded one-time programmable (OTP) memory</td>
<td>No</td>
</tr>
<tr>
<td>Embedded 1.5V regulator for core power</td>
<td>Yes</td>
</tr>
</tbody>
</table>
<h2>Software Features</h2>
<p>Full documentation of the camera software can be found at <a href="../raspbian/applications/camera.md">raspbian/applications/camera</a>.</p>
<table>
<thead>
<tr>
<th></th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td>Picture formats</td>
<td>JPEG (accelerated) , JPEG + RAW , GIF , BMP , PNG , YUV420 , RGB888</td>
</tr>
<tr>
<td>Video formats</td>
<td>raw h.264 (accelerated)</td>
</tr>
<tr>
<td>Effects</td>
<td>negative , solarise , posterize , whiteboard , blackboard , sketch , denoise , emboss , oilpaint , hatch , gpen , pastel , watercolour,  film , blur , saturation</td>
</tr>
<tr>
<td>Exposure modes</td>
<td>auto  , night , nightpreview , backlight , spotlight , sports , snow , beach , verylong  , fixedfps , antishake , fireworks</td>
</tr>
<tr>
<td>Metering modes</td>
<td>average, spot, backlit, matrix</td>
</tr>
<tr>
<td>Automatic White Balance modes</td>
<td>off, auto , sun , cloud, shade, tungsten, fluorescent , incandescent , flash, horizon</td>
</tr>
<tr>
<td>Triggers</td>
<td>Keypress , UNIX signal , timeout</td>
</tr>
<tr>
<td>Extra modes</td>
<td>demo , burst/timelapse , circular buffer , video with motion vectors , segmented video , live preview on 3D models</td>
</tr>
</tbody>
</table>
</article>
