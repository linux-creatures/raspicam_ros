<!DOCTYPE html>
<!--[if IE 7]>
<html class="ie ie7" lang="en-GB">
<![endif]-->
<!--[if IE 8]>
<html class="ie ie8" lang="en-GB">
<![endif]-->
<!--[if !(IE 7) | !(IE 8)  ]><!-->
<html lang="en-GB">
<!--<![endif]-->
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, user-scalable=no" />
    <title>Raspberry Pi Documentation</title>
    <link rel="icon" type="image/png" href="/wp-content/themes/mind-control/images/favicon.png" />
    <link rel="publisher" href="https://plus.google.com/+RaspberryPi" />
    <!--[if lt IE 9]>
    <script src="/wp-content/themes/mind-control/js/html5.js"></script>
    <![endif]-->

    <link rel="stylesheet" href="/wp-content/themes/mind-control/css/prism.css" />
    <link rel="stylesheet" href="/wp-content/themes/mind-control/style.css" />
    <link rel="stylesheet" href="/wp-content/themes/mind-control/mobile.css" />
    <link rel="stylesheet" href="//fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700">
    <link rel="stylesheet" href="//fonts.googleapis.com/css?family=Roboto:100italic,100,300italic,300,400italic,400,500italic,500,700italic,700,900italic,900">
    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>
    <script src="/wp-content/themes/mind-control/js/jquery.main.js"></script>
    <script src="/wp-content/themes/mind-control/js/prism.js"></script>

    <script type="text/javascript">//<![CDATA[
        // Google Analytics for WordPress by Yoast v4.3.5 | //yoast.com/wordpress/google-analytics/
        var _gaq = _gaq || [];
        _gaq.push(['_setAccount', 'UA-46270871-1']);
			            _gaq.push(['_trackPageview']);
        (function () {
            var ga = document.createElement('script');
            ga.type = 'text/javascript';
            ga.async = true;
            ga.src = ('https:' == document.location.protocol ? 'https://ssl' : '//www') + '.google-analytics.com/ga.js';

            var s = document.getElementsByTagName('script')[0];
            s.parentNode.insertBefore(ga, s);
        })();
        //]]></script>

    <link rel='canonical' href='//www.raspberrypi.org/' />
    <link rel='shortlink' href='//www.raspberrypi.org/' />
</head>

<body class="documentation">
    <div class="container">
        <header id="header">
            <nav id="nav">
                <ul id="menu-nav-bar" class="menu"><li id="menu-item-6901" class="home mobile menu-item menu-item-type-post_type menu-item-object-page current-menu-item page_item page-item-5372 current_page_item menu-item-6901"><a href="/">Home</a></li>
                    <li id="menu-item-8279" class="close-menu menu-item menu-item-type-custom menu-item-object-custom menu-item-8279"><a href="#">Close Menu</a></li>
                    <li id="menu-item-6902" class="yellow menu-item menu-item-type-post_type menu-item-object-page menu-item-6902"><a href="/blog/">Blog</a></li>
                    <li id="menu-item-6903" class="red menu-item menu-item-type-post_type menu-item-object-page menu-item-6903"><a href="/downloads/">Downloads</a></li>
                    <li id="menu-item-6904" class="purple menu-item menu-item-type-post_type menu-item-object-page menu-item-6904"><a href="/community/">Community</a></li>
                    <li id="menu-item-6905" class="green menu-item menu-item-type-post_type menu-item-object-page menu-item-6905"><a href="/help/">Help</a></li>
                    <li id="menu-item-6907" class="pink menu-item menu-item-type-custom menu-item-object-custom menu-item-6907"><a href="/forums/">Forums</a></li>
                    <li id="menu-item-6908" class="blue menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-6908"><a href="/resources/">Resources</a>
                        <ul class="sub-menu">
                        	<li id="menu-item-6911" class="blue2 menu-item menu-item-type-taxonomy menu-item-object-resource-category menu-item-6911"><a href="/resources/teach/">Teach</a></li>
                        	<li id="menu-item-6909" class="blue3 menu-item menu-item-type-taxonomy menu-item-object-resource-category menu-item-6909"><a href="/resources/learn/">Learn</a></li>
                        	<li id="menu-item-6910" class="blue4 menu-item menu-item-type-taxonomy menu-item-object-resource-category menu-item-6910"><a href="/resources/make/">Make</a></li>
                        </ul>
                    </li>
                    <li id="menu-item-7165" class="menu mobile menu-item menu-item-type-custom menu-item-object-custom menu-item-7165"><a href="#">Menu</a></li>
                    <li id="menu-item-6912" class="search mobile menu-item menu-item-type-custom menu-item-object-custom menu-item-6912"><a href="#">Search</a></li>
                    <li id="menu-item-7154" class="shop menu-item menu-item-type-post_type menu-item-object-page menu-item-7154"><a href="/buy/">Buy</a></li>
                </ul>
            </nav>
            <form class="search" action="/">
                <input name="s" class="search" value="" />
                <input type="submit" class="submit" value="Search" />
            </form>
        </header>

        <div class="main">

<nav class="breadcrumbs">
    <a href='http://www.raspberrypi.org/documentation'>documentation</a> &gt; <a href='http://www.raspberrypi.org/documentation/hardware'>hardware</a> &gt; camera</nav>

<article class="entry-content">

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

                <footer class="licence">
                    <aside class="octocat">
                        <a href="https://github.com/raspberrypi/documentation/blob/master/hardware/camera.md"><img src="/wp-content/themes/mind-control/images/octocat.jpg" /></a>
                    </aside>
                    <aside class="links">
                        <a href="https://github.com/raspberrypi/documentation/blob/master/hardware/camera.md" class="github">View/Edit this page on GitHub</a><br />
                        <a href="/creative-commons/">Read our usage and contributions policy</a><br />
                        <a href="/creative-commons/" class="cc"><img src="//i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons Licence"></a>
                    </aside>
                </footer>

                <div style="clear: both;"></div>

            </div>

            <div style="clear: both;"></div>

            <aside id="social-icons" class="footer">
                <div class="footer-contents">
                    <ul id="menu-social-icons" class="menu">
                        <li id="menu-item-6924" class="twitter menu-item menu-item-type-custom menu-item-object-custom menu-item-6924"><a href="https://twitter.com/Raspberry_Pi">@Raspberry_Pi on Twitter</a></li>
                        <li id="menu-item-6925" class="googleplus menu-item menu-item-type-custom menu-item-object-custom menu-item-6925"><a href="https://plus.google.com/+RaspberryPi">+RaspberryPi on Google+</a></li>
                        <li id="menu-item-6926" class="facebook menu-item menu-item-type-custom menu-item-object-custom menu-item-6926"><a href="https://www.facebook.com/raspberrypi">Raspberry Pi on Facebook</a></li>
                        <li id="menu-item-6927" class="github menu-item menu-item-type-custom menu-item-object-custom menu-item-6927"><a href="https://github.com/raspberrypi">Raspberry Pi on GitHub</a></li>
                        <li id="menu-item-6928" class="githublearning menu-item menu-item-type-custom menu-item-object-custom menu-item-6928"><a href="https://github.com/raspberrypilearning">Raspberry Pi Learning on GitHub</a></li>
                        <li id="menu-item-6929" class="youtube menu-item menu-item-type-custom menu-item-object-custom menu-item-6929"><a href="https://www.youtube.com/channel/UCFIjVWFZ__KhtTXHDJ7vgng">Raspberry Pi on YouTube</a></li>
                        <li id="menu-item-6930" class="vimeo menu-item menu-item-type-custom menu-item-object-custom menu-item-6930"><a href="https://vimeo.com/raspberrypi">Raspberry Pi on Vimeo</a></li>
                    </ul>
                </div>
            </aside>

        <footer id="footer">
            <div class="footer-contents">
                <ul id="menu-about-us" class="menu">
                    <li id="menu-item-6888" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-6888"><a href="/about/">About us</a></li>
                    <li id="menu-item-6892" class="menu-item menu-item-type-post_type menu-item-object-help menu-item-6892"><a href="/help/faqs/">FAQs</a></li>
                    <li id="menu-item-6893" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-6893"><a href="/cookies/">Cookies</a></li>
                    <li id="menu-item-6895" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-6895"><a href="/creative-commons/">Creative Commons</a></li>
                    <li id="menu-item-6896" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-6896"><a href="/trademark-rules/">Trademark rules</a></li>
                    <li id="menu-item-6898" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-6898"><a href="/contact-us/">Contact us</a></li>
                </ul>

                <footer>
                    Raspberry Pi Foundation<br />
                    UK registered charity 1129409
                </footer>
            </div>
        </footer>
    </div>
</body>
</html>
