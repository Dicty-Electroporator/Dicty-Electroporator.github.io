<h2><p><em>Dictyostelium</em> <em>discoideum</em> Electroporator</p></h2>

<p><a href="https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/tree/master/Dictyostelium%20discoideum%20Electroporator">Download Project</a></p>
<p><strong>Abstract:&nbsp;</strong>Custom-made, inexpensive and open-source electroporation apparatus for <em>Dictyostelium discoideum</em> with all functional modules and peripherals.</p>
<p><strong>Description:&nbsp;</strong>Electroporation to introduce DNA into cells is a common technique in genetic engineering. Dictyostelium discoideum is a well-established eukaryotic model organism that is frequently genetically modified (transformed). We present here an electroporator capable of high efficiency D. discoideum transformation. Our electroporator consists of a high voltage power supply, pulse generator circuit and cell sample cuvette holder. The power supply is programmed to deliver desired voltage, which when activated by a double-pole, double-throw switch (DPDT below) charges the capacitor. Further switching allows the charged capacitor to deliver a precise, consistent exponential decay wave of the proper duration to the cuvette containing a D. discoideum cell and DNA mixture. The high-voltage circuit is housed in an electrically insulated enclosure - we chose a plastic electrical junction box with appropriate holes for switch mounting and cables to pass.  A 3D printable cuvette holder was designed and is available in .stl, .dwg and .iges formats. An electrophoresis chamber cover with cables was used as an adapter for banana plug/jack connections to the power supply. Integral in development and testing was an inexpensive 1,000-volt digital multimeter. To provide hands-free monitoring of discharge circuit voltage and monitoring of the real-time capacitor voltage, we connected the multimeter to the cuvette holder or to the capacitor plates with 24-inch male-male banana test leads or alligator clips, respectively. At the end of these instructions we have included safety and durability enhancements for a second generation prototype.</p>

![](figs/pic%201.png)
![](figs/pic%202.PNG)

<p><strong>License:&nbsp;</strong>CERN Open Hardware License</p>

<h1><p>2nd Generation Enhanced Prototype</p></h1>
![](figs/pic%202.PNG)

<p>For those concerned with a more durable and potentially safer device we have also constructed and tested an additional prototype with a minimal increase in cost. The second prototype features a soldered breadboard with higher power components. Assembly of the pulse generator circuit is straightforward and can be constructed by a beginner with access to soldering equipment. Improved safety features include an inverted capacitor on a circuit board that is solid state. The second prototype cuvette chamber requires more print media but includes an enclosure with more limited access to the power connectors as well as a clear removable lid. The 3D design and print files are available on this page. Note that we chose a biodegradable and fire-resistant 3D print media. There are other cost effective, readily available, and more durable print media available. The enhanced system was tested and performs as efficiently as the original prototype.</p>

<p>A soldered Pulse Generator was made with much higher wattage resistors and terminal plugs for the switch.</p>
![](figs/Gen2SwPlugsCloseup.jpg)
<p>&nbsp;</p>
<p>For a more durable device 2W-1M Ohm resistors were used for the anti-no-load shutoff resistors R1-R2 and bleed down resistors R9-R12. 8W-100k Ohm resistors were used for charge-side current limiting shutoff resistors R3-R8.</p>
![](figs/Gen2PGRt.jpg)
<p>&nbsp;</p>
<p>The components were fixed to the breadboard using the long leads of resistors as traces on the underside of the 8cm x 12cm padboard.</p>
![](figs/Placement.PNG)
![](figs/Gen2Traces2.jpg)
<p>Trimmed resistor terminals were used to create any additional traces. This technique can easily be found on the internet. While the circuit diagram has remained unchanged, the new board layout accommodates the lack of premade traces found on solderless breadboards. In addition, two jumper wires were soldered to the component side at each end of the bleed-down resistor array. This modification allows the real-time monitoring of the capacitor voltage during electroporation and provides assurance the capacitor is safe. This is accomplished by connecting the 1kV digital multimeter to the jumper wires using alligator clips passed through newly drilled holes in the enclosure. The same digital multimeter used for performing a functions check may be used.</p>
<p>&nbsp;</p>
<h2><p>2nd generation enhanced cuvette chamber</p></h2>
<p>The second-generation enhanced prototype cuvette holder has several additional safety features. The original cuvette holder is now enclosed in a four-sided box with a removable clear Poly acrylic lid. Collars have been enlarged to add additional protection from shock exposure. Design and print files have been included below and the chamber can be printed either hollow or solid.</p>

![](figs/Gen2CHcollars.jpg)
![](figs/Gen2CHlid.jpg)
<p><strong>Print File2:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/master/Enhanced%20Cuvette%20Chamber%203DPrintSTL.stl">Enhanced Cuvette Chamber.stl</a></strong></p>
<p><strong>CAD Design File2:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/master/Enhanced%20Cuvette%20Chamber%20CAD.dwg">Enhanced Cuvette Chamber.dwg</a></strong></p>
<p>FreeCAD Open Source IGES Design File: Available in Download Project top of page</p>

<p><strong>Enclosure Lid Print File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/master/Enclosure%20Lid%20STL.stl">Enclosure Lid STL.stl</a></strong></p>
<p><strong>Enclosure Lid CAD Design File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/master/Enclosure%20Lid%20CAD.dwg">Enclosure Lid CAD.dwg</a></strong></p>
<p>Laser Cut Enclosure Lid SVG File: Available in Download Project top of page</p>
<p>FreeCAD Open Source IGES Design File: Available in Download Project top of page</p> 

<p>&nbsp;</p>
<h2><p>Additional parts required for the enhanced prototype</p></h2>

<table>
<thead>
<tr>
<td>
<p><strong>Part</strong></p>
</td>
 
<td>
<p><strong>Quantity</strong></p>
</td>
 
<td>
<p><strong>Supplier</strong></p>
</td>
 
<td>
<p><strong>Supplier part number</strong></p>
</td>
 
<td>
<p><strong>URL</strong></p>
</td>
</tr>
</thead>
  
 <tr>    
<td>
<p>Power supply banana plug test leads 60 inch</p>
</td>
 
<td>
<p>1-2</p>
</td>
 
<td>
<p>Mouser</p>
</td>
 
<td>
<p>4911A-60/4911A-62</p>
</td>
 
<td>
<p><a href="https://www.mouser.com/Search/Refine?Keyword=4911a-60">www.mouser.com</a></p>
</td>
 </tr>
  <tr>
<td>
<p>PCB Prototype padboard - 8cm x 12cm</p>
</td>
 
<td>
<p>1</p>
</td>
 
<td>
<p>Amazon</p>
</td>
 
<td>
<p>739340318574</p>
</td>
 
<td>
<p><a href="https://www.amazon.com/gp/product/B07Y3DVM1W/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1">www.amazon.com</a></p>
</td>
 </tr> 
  <tr>
<td>
<p>Resistors - 8W-100k Ohm</p>
</td>
 
<td>
<p>6</p>
</td>
 
<td>
<p>Mouser</p>
</td>
 
<td>
<p>279-ROX8J100K</p>
</td>
 
<td>
<p><a href="https://www.mouser.com/ProductDetail/TE-Connectivity-Holsworthy/ROX8J100K?qs=gZXFycFWdAMYKZPoGrub8g%3D%3D">www.mouser.com</a></p>
</td>
 </tr> 
  <tr>
<td>
<p>Resistors - 2W-1M Ohm</p>
</td>
 
<td>
<p>6</p>
</td>
 
<td>
<p>Mouser</p>
</td>
 
<td>
<p>594-5083NW1M000J</p>
</td>
 
<td>
<p><a href="https://www.mouser.com/ProductDetail/Vishay-BC-Components/PR02000201004JR500?qs=LCMWAU1DZcwmgZ1lvVsGww%3D%3D">www.mouser.com</a></p>
</td>
 </tr>
  <tr>
<td>
<p>Bio-Rad Model 3000xi Computer Controlled Electrophoresis Power Supply</p>
</td>
 
<td>
<p>1</p>
</td>
   
<td>
<p>ebay</p>
</td>
   

   
<td>
<p><a href="https://www.ebay.com">www.ebay.com</a></p>
</td>

  <tr>
<td>
<p>3-Pin 5.08mm Pitch Male Female Plug-in PCB Screw Terminal Block Connector</p>
</td>
   
<td>
<p>2</p>
</td>
   
<td>
<p>Amazon</p>
</td>
   
<td>
<p>0766832280286</p>
</td>
<td>
<p><a href="https://www.amazon.com/PoiLee-5-08mm-Female-Terminal-Connector/dp/B07TQLYQ7W/ref=asc_df_B07TQLYQ7W/?tag=hyprod-20&linkCode=df0&hvadid=385629037133&hvpos=&hvnetw=g&hvrand=8172029133657464055&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9005131&hvtargid=pla-846156762614&psc=1&tag=&ref=&adgrpid=73872201970&hvpone=&hvptwo=&hvadid=385629037133&hvpos=&hvnetw=g&hvrand=8172029133657464055&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9005131&hvtargid=pla-846156762614">www.amazon.com</a></p>
 </tr?
  
<p>&nbsp;</p>

<p><strong>Requires:</strong></p>

<ul>
<li>Pulse Generator&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Cuvette Holder&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Multimeter&nbsp;<strong>x&nbsp;1,&nbsp;</strong>1KV DC Power supply (e.g., Bio-Rad PowerPac 1000+)&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Red banana plug test lead - 24 inch&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Black banana plug test lead - 24 inch&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Horizontal Gel Electrophoresis System&nbsp;<strong>x&nbsp;1</strong></li>
</ul>

<h3><p>Assembly instruction</p></h3>
<p><strong>Step&nbsp;1.&nbsp;</strong>Plug electroporator power supply leads into gel electrophoresis lid.</p>
<p><strong>Step&nbsp;2.&nbsp;</strong>Plug electrophoresis lid leads into power supply.</p>
<p><strong>Step&nbsp;3.&nbsp;</strong>Plug electroporator cuvette leads into cuvette holder.</p>
<p><strong>Step&nbsp;4.&nbsp;</strong>Plug 24-inch male-male banana test leads into digital multimeter and the other end into the female end of stackable banana jacks of Step 2.</p>
<p><strong>Step&nbsp;5.&nbsp;</strong>Perform functions check: power on the digital multimeter, set to measure voltage (up to 1KV), and charge &amp; discharge the capacitor with the pulse generator switch at lower voltage (e.g. 75V). If the device is functioning correctly, when the discharge begins the multimeter will display approximately 75V and go to ~50V volts in about 30sec.</p>
<p>&nbsp;</p>
<h2><p>Enclosure</p></h2>
<p><strong>Description:&nbsp;</strong>We chose to purchase a commercially available plastic junction box to enclose our pulse generator circuit. A 13mm hole was drilled into the enclosure cover for the DPDT and 22mm holes were marked and drilled in the enclosure which provided a nice fit for the plastic NM connectors and pass-through cables.</p>
![](figs/encl.jpg)
<p><strong>Requires:</strong></p>
<ul>
<li>Junction box&nbsp;<strong>x&nbsp;1</strong></li>
</ul>
<h4><p>Assembly instruction</p></h4>
![](figs/encl%201.png)
<p><strong>Step&nbsp;1.&nbsp;</strong>Drill two 22mm holes in any side of the enclosure with centers at 34mm from the exterior bottom and horizontally 46mm apart on center. It might be helpful to label one hole &ldquo;Power supply&rdquo; and the other &ldquo;Cuvette holder&rdquo;.</p>
![](figs/encl%202.jpg)
<p><strong>Step&nbsp;2.&nbsp;</strong>Drill 13mm hole in enclosure lid for switch mounting. Place the hole where hand-switching will be most comfortable.</p>
<p>&nbsp;</p>
<h2><p>Pulse Generator</p></h2>
<p><strong>Description:&nbsp;</strong>Components and configurations of the electrical circuit are described here. For all connections, refer to the circuit diagram and photos of the assembled circuit.</p>
![](figs/pgen%201.png)
![](figs/pgen%202.jpg)
<p><strong>Requires:</strong></p>
<ul>
<li>400 Point solderless breadboard&nbsp;<strong>x&nbsp;2,&nbsp;</strong>24AWG Male-Male fixed length jumper wires&nbsp;<strong>x&nbsp;5,&nbsp;</strong>Test Lead Wire 25 ft. red&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Test Lead Wire 25 ft. black&nbsp;<strong>x&nbsp;1,&nbsp;</strong>26AWG Male-Male flexible jumper wires&nbsp;<strong>x&nbsp;9,&nbsp;</strong>Capacitor - 25microF 1.3kV&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Red banana plug test lead - 60 inch&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Black banana plug test lead - 60 inch&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Ring Terminals&nbsp;<strong>x&nbsp;4,&nbsp;</strong>Resistor - 1M Ohm 1/2W&nbsp;<strong>x&nbsp;6,&nbsp;</strong>Resistor - 100k Ohm 2W&nbsp;<strong>x&nbsp;6,&nbsp;</strong>14-26 AWG 3-Position Screw Terminal Block&nbsp;<strong>x&nbsp;4,&nbsp;</strong>15A AC DPDT toggle switch&nbsp;<strong>x&nbsp;1,&nbsp;</strong>Plastic NM Connector&nbsp;<strong>x&nbsp;2,&nbsp;</strong>Enclosure&nbsp;
<strong>x&nbsp;1</strong></li>
</ul>
<p>&nbsp;</p>
<h3><p>Assembly instruction</p></h3>
<p>&nbsp;</p>
![](figs/pgen%20assmb%201.png)
<p><strong>Step&nbsp;1.&nbsp;</strong>Cut 4 pieces of 18 AWG wire (for the switch) to 30cm lengths and strip approx. 5mm of bare wire from each end. Crimp one end of each wire to a ring terminal.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%202.1.jpg)
![](figs/pgen%20assmb%202.2.png)
<p><strong>Step&nbsp;2.&nbsp;</strong>Attach ring terminals (with wire from step 1) to terminals 2, 3, 4, and 5 of the DPDT switch. Install switch into hole drilled into lid of case.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%203.jpg)
<p><strong>Step&nbsp;3.&nbsp;</strong>Using the 4 pieces of 18 AWG wire with ring terminals from step 1, connect switch terminals 2 and 3 to the outboard ports of one terminal block and 4 and 5 to the outboard ports of another terminal block by inserting paired wires into outside wire cages of terminal blocks, then tighten terminal block screws.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%204.jpg)
<p><strong>Step&nbsp;4.&nbsp;</strong>Clip resistor pins and bend at 90-degree angle to fit into breadboard terminals.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%205.jpg)
<p><strong>Step&nbsp;5.&nbsp;</strong>Connect six 100K Ohm - 2W resistors (R3-R8) in parallel into breadboards using jumper wires as needed to form connections.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%206.png)
<p><strong>Step&nbsp;6.&nbsp;</strong>Connect two 1M Ohm - 1/2W resistors (R1 and R2) in series into breadboards using jumper wires as needed to form connections.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%207.png)
<p><strong>Step&nbsp;7.&nbsp;</strong>Connect four 1M Ohm - 1/2W resistors (R9-R12) in series. A short jumper wire is also placed on the board as shown (lower right section of breadboard) that will become a link between terminal blocks from steps 2, 3, 9 and 10.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%208.1.png)
![](figs/pgen%20assmb%208.2.jpg)
![](figs/pgen%20assemb%208.3.jpg)
<p><strong>Step&nbsp;8.&nbsp;</strong>Ensure the 25microF - 1,300V capacitor is not charged before handling by measuring voltage across the terminals using the multimeter. Connect three 20cm flexible jumper wires to each pole of capacitor. Note that two leads from each capacitor pole are present. Wire terminals can be crimped around capacitor leads or soldered for establishing a more permanent connection. Attach capacitor leads to breadboard per circuit diagram.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%209.1.jpg)
![](figs/pgen%20assemb%209.2.jpg)
<p><strong>Step&nbsp;9.&nbsp;</strong>Connect terminal blocks from switch leads to breadboard (see step 3).</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%2010.1.jpg)
![](figs/pgen%20assemb%2010.2.png)
<p><strong>Step&nbsp;10.&nbsp;</strong>Cut 1 red and 1 black 60 in. test lead in half. Strip cut ends to leave approximately 5mm of bare wire. It might be helpful to tape the two pairs of one red and one black wire together every few centimeters. Pass stripped wire ends through NM plastic connectors about 10cm. Connect terminal blocks to the stripped ends by inserting paired wires into outside wire cages of terminal blocks, then tighten terminal block screws. Push NM plastic connectors into the cable pass-through holes of the enclosure.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%2011.png)
<p><strong>Step&nbsp;11.&nbsp;</strong>Pull the terminal block ends of the power supply and cuvette holder cables further through the pass-through holes with only sufficient play to insert the terminal blocks into the appropriate places on the breadboards.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%2012.png)
<p><strong>Step&nbsp;12.&nbsp;</strong>Adhere the breadboards and capacitor to the inside base of the enclosure. While we used 2-sided tape, glue could be used for a more permanent solution. Connect power supply and cuvette holder terminal blocks to breadboard.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%2013.png)
<p><strong>Step&nbsp;13.&nbsp;</strong>Attach enclosure cover.</p>
<p>&nbsp;</p>




<h2><p>Cuvette Holder</p></h2>
<p><strong>Description:&nbsp;</strong>The cuvette holder provides the delivery vehicle for the electric field that causes electroporation. It is also notable that the cuvette holder was designed to keep inward pressure on the plug ends that contact the cuvette. It was an important consideration in our design to provide hands-free electroporation and the built-in spring-like nature of the resulting connection ensures constant contact - even when like charges build up on each plug and its corresponding cuvette contact - a force that opposes contact. It is also notable that we chose stackable banana plugs so that we could tandem a 1,000V multimeter to the cuvette holder - especially useful during pre-electroporation functions check.</p>

<p><strong>Requires:</strong></p>
<ul>
<li>3D printed cuvette holder&nbsp;<strong>x&nbsp;1</strong></li>
</ul>
<h4><p>Assembly instruction</p></h4>
![](figs/cuv%201.png)
![](figs/cuv%202.jpg)
![](figs/cuv%203.png)
<p><strong>Step&nbsp;1.&nbsp;</strong>3D print a Cuvette holder in PLA semi-hollow and without support. A print file is available below in STL format. An editable design file in DWG format is also available below. The DWG file was created in AutoCAD student edition which is free for students. The DWG file is also editable in several open-source CAD packages including DraftSight, Autodesk 123D Design, nanoCAD, AutoCAD Mobile and DoubleCAD XT. Another open-source CAD package we have accommodated is FreeCAD, which can edit IGES files. An IGES design file is available through the link Download Project at the top of this page.</p>

<p><strong>Print File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/master/Cuvette%20Holder.stl">Cuvette Holder.stl</a></strong></p>
<p><strong>CAD Design File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/master/Cuvette%20Holder.dwg">Cuvette Holder.dwg</a></strong></p>
<p>FreeCAD Open Source IGES Design File:&nbsp;Available in Download Project top of page</p>
<p>&nbsp;</p>

<h2><p>Authors</p></h2>
<table>
<thead>
<tr>
<td>
<p><strong>Name</strong></p>
</td>
<td>
<p><strong>E-mail</strong></p>
</td>
<td>
<p><strong>Affiliation</strong></p>
</td>
<td>&nbsp;</td>
</tr>
</thead>
<tbody>
<tr>
<td>
<p>Michael Cauchy</p>
</td>
<td>
<p>mcauchy@oswego.edu</p>
</td>
<td>
<p>State University of New York at Oswego</p>
</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
<p>Ali A. Khan</p>
</td>
<td>
<p>akhan3@oswego.edu</p>
</td>
<td>
<p>State University of New York at Oswego</p>
</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
<p>Yulia Artemenko</p>
</td>
<td>
<p>yulia.artemenko@oswego.edu</p>
</td>
<td>
<p>State University of New York at Oswego</p>
</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
<p>David A. Dunn</p>
</td>
<td>
<p>david.dunn@oswego.edu</p>
</td>
<td>
<p>State University of New York at Oswego</p>
</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
<h2><p>Total bill of materials for this project</p></h2>
<table>
<thead>
<tr>
<td>
<p><strong>Part</strong></p>
</td>
<td>
<p><strong>Quantity</strong></p>
</td>
<td>
<p><strong>Supplier</strong></p>
</td>
<td>
<p><strong>Supplier part number</strong></p>
</td>
<td>
<p><strong>URL</strong></p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td>
<p>400 Point solderless breadboard</p>
</td>
<td>
<p>2</p>
</td>
<td>
<p>Jameco</p>
</td>
<td>
<p>2157693</p>
</td>
<td>
<p><a href="http://www.jameco.com">www.jameco.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Male-Male fixed length jumper wires</p>
</td>
<td>
<p>5</p>
</td>
<td>
<p>Jameco</p>
</td>
<td>
<p>2127718</p>
</td>
<td>
<p><a href="https://www.jameco.com/z/WJW-70B-5-70-Piece-Jumper-Wire-Kit-22AWG-14-Lengths-10-Colors_2127718.html">www.jameco.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Test Lead Wire 25 in. red</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Powerwerx</p>
</td>
<td>
<p>Wire-TL-18-00-25</p>
</td>
<td>
<p><a href="https://powerwerx.com/test-lead-rubber-flexible-wire">powerwerx.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Test Lead Wire 25 in. black</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Powerwerx</p>
</td>
<td>
<p>Wire-TL-18-00-25</p>
</td>
<td>
<p><a href="https://powerwerx.com/test-lead-rubber-flexible-wire">powerwerx.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Male-Male flexible jumper wires</p>
</td>
<td>
<p>9</p>
</td>
<td>
<p>Mouser</p>
</td>
<td>
<p>KIT-ZWx4</p>
</td>
<td>
<p><a href="https://www.mouser.com/ProductDetail/BusBoard-Prototype-Systems/KIT-ZWx4?qs=sGAEpiMZZMvh1pRuiUVjFZ0aAJXGPyuNDJiA5Z8ZR2Q%2FfInvTU3aKA%3D%3D">www.mouser.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Capacitor - 25microF - 1,300V</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Mouser</p>
</td>
<td>
<p>C4AQUBW5250A3NJ</p>
</td>
<td>
<p><a href="https://www.mouser.com/ProductDetail/KEMET/C4AQUBW5250A3NJ?qs=%2Fha2pyFadugKSuBjMOjke5u9ridkq4YeClSJSpnddrBZ2GZPnEOejQ%3D%3D">www.mouser.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Red banana plug test lead - 60 inch</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Mouser</p>
</td>
<td>
<p>B-60-2</p>
</td>
<td>
<p><a href="https://www.mouser.com/ProductDetail/Pomona-Electronics/B-60-2?qs=sGAEpiMZZMv8kklI404QlQaMEaX1aQ14">www.mouser.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Black banana plug test lead - 60 inch</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Mouser</p>
</td>
<td>
<p>B-60-0</p>
</td>
<td>
<p><a href="https://www.mouser.com/ProductDetail/Pomona-Electronics/B-60-0?qs=sGAEpiMZZMv8kklI404QlV4QPmgLmIZb">www.mouser.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Ring Terminals</p>
</td>
<td>
<p>4</p>
</td>
<td>
<p>Lowes</p>
</td>
<td>
<p>136093</p>
</td>
<td>
<p><a href="https://www.lowes.com/pd/Utilitech-20-Count-Ring-Wire-Connectors/999953294">www.lowes.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Resistor - 1M Ohm - 500mW</p>
</td>
<td>
<p>6</p>
</td>
<td>
<p>Mouser</p>
</td>
<td>
<p>71-CMF551M0000BHEK</p>
</td>
<td>
<p><a href="https://www.mouser.com/ProductDetail/Vishay-Dale/CMF551M0000BHEK?qs=rMX6kfwPG0qbAzHtP4OjAA%3D%3D">www.mouser.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Resistor - 100k Ohm - 2W</p>
</td>
<td>
<p>6</p>
</td>
<td>
<p>Amazon</p>
</td>
<td>
<p>60PCS 2W Resistor</p>
</td>
<td>
<p><a href="https://www.amazon.com/BAEASU-60PCS-Metal-Film-Resistor/dp/B07VCDJR8W?th=1">www.amazon.com</a></p>
</td>
</tr>
<tr>
<td>
<p>3-Position Screw Terminal Block</p>
</td>
<td>
<p>4</p>
</td>
<td>
<p>Addicore</p>
</td>
<td>
<p>AD305</p>
</td>
<td>
<p><a href="https://www.addicore.com/3-Position-Screw-Terminal-Block-p/ad305.htm">www.addicore.com</a></p>
</td>
</tr>
<tr>
<td>
<p>DPDT toggle switch - 20A</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Ace Hardware</p>
</td>
<td>
<p>GSW-16</p>
</td>
<td>
<p><a href="https://www.acehardware.com/departments/lighting-and-electrical/switches-outlets-and-plugs/switches/3531324">www.acehardware.com</a></p>
</td>
</tr>
<tr>
<td>
<p>3/8-in Plastic NM Connector</p>
</td>
<td>
<p>2</p>
</td>
<td>
<p>Lowes</p>
</td>
<td>
<p>44740</p>
</td>
<td>
<p><a href="https://www.lowes.com/pd/Sigma-Electric-ProConnex-3-8-in-Snap-in-Connector-Conduit-Fitting/3151125">www.lowes.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Junction box</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Lowes</p>
</td>
<td>
<p>E987NR</p>
</td>
<td>
<p><a href="https://www.lowes.com/pd/CARLON-Gray-Weatherproof-Pvc-Junction-Box/1000975650">www.lowes.com</a></p>
</td>
</tr>
<tr>
<td>
<p>3D printed cuvette holder</p>
</td>
<td>
<p>1</p>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
<p>Multimeter</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>CEN-TECH</p>
</td>
<td>
<p>61593/P37772</p>
</td>
<td>
<p><a href="https://www.harborfreight.com/11-function-digital-multimeter-with-audible-continuity-61593.html">www.harborfreight.com</a></p>
</td>
</tr>
<tr>
<td>
<p>1KV DC Power supply (e.g., Bio-Rad PowerPac 1000)</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Bio-Rad (or other)</p>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
<p>Red banana plug test lead - 24 inch - 15A</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Mouser</p>
</td>
<td>
<p>B-24-2</p>
</td>
<td>
<p><a href="https://www.mouser.com/ProductDetail/Pomona-Electronics/B-24-2?qs=Jz4yJwmcGUolf%2Ft6R9QPRg%3D%3D">www.mouser.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Black banana plug test lead - 24 inch</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Mouser</p>
</td>
<td>
<p>B-24-0</p>
</td>
<td>
<p><a href="https://www.mouser.com/ProductDetail/Pomona-Electronics/B-24-0?qs=sGAEpiMZZMvdy8WAlGWLcB2mHTMXCqDa">www.mouser.com</a></p>
</td>
</tr>
<tr>
<td>
<p>Horizontal Gel Electrophoresis System</p>
</td>
<td>
<p>1</p>
</td>
<td>
<p>Thermo Fisher Scientific</p>
</td>
<td>
<p>FB-SB-710 (or similar)</p>
</td>
<td>
<p><a href="https://www.fishersci.com/shop/products/fisherbiotech-horizontal-electrophoresis-systems-minigel-system-7-x-10cm-gel-size/fbsb710">www.fishersci.com</a></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>

