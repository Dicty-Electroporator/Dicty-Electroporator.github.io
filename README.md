<h2>
   <p><em>Dictyostelium</em> <em>discoideum</em> Electroporator</p>
</h2>
<p><a href="https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/tree/Gen-2.1-with-edits/Dictyostelium%20discoideum%20Electroporator">Download Project</a></p>
<p>Easily constructed by investigators with no electronics knowledge, we present an inexpensive and open-source electroporation apparatus for <em>Dictyostelium discoideum</em> with all functional modules and peripherals from Cauchy et al., 2022, "A Low-cost Electroporator for Genetically Modifying Social Amoeba <em>Dictyostelium discoideum</em>" submitted to Journal of Open Hardware.</p>
<p><strong>Description:&nbsp;</strong>Electroporation to introduce DNA into cells is a common technique in genetic engineering. <em>Dictyostelium discoideum</em> is a well-established eukaryotic model organism that is frequently genetically modified (transformed). We present here an electroporator capable of high efficiency transformation. Our electroporator consists of a high voltage power supply, pulse generator circuit and cell sample cuvette chamber. The power supply is programmed to deliver desired voltage, which when activated by a double-pole, double-throw switch (DPDT) charges a capacitor. Further switching allows the charged capacitor to deliver a precise, consistent exponential decay wave of the proper duration to the cuvette containing a <em>D. discoideum</em> cell and DNA mixture. The high-voltage circuit is housed in an electrically insulated enclosure - we chose a plastic electrical junction box with appropriate holes for switch mounting and cables to pass. A 3D printable cuvette holder was designed and is available in .stl, .dwg and .iges formats. An inexpensive 1,000-volt digital multimeter was integrated into the design to aid in development and testing. To provide hands-free monitoring of the real-time capacitor voltage, we connected multimeter test leads to the capacitor poles. In addition to the standard build, we present here an alternative design for the pulse generator, which we will refer to as "modular". The standard pulse generator was designed to be durable for repeated use in multiple <em>D. discoideum</em> electroporation experiments. This design includes a soldered padboard with high power rated components. The modular pulse generator is designed for ease of build, is easily modified by swapping components for alternative waveforms, and is intended for a small number of electroporations and not routine or repeated use.</p>
 
 
<p><strong>License:&nbsp;</strong><a href="https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/blob/Base/LICENSE">CERN Open Hardware License</a></p>
<p>&nbsp;</p> 
<h1>
   <p><em>D. discoideum</em> Electroporation System</p>
</h1>
![](figs/pic%202.png)
<h2>
   <p>Standard Pulse Generator</p>
</h2>
<p>The pulse generator circuit features a soldered breadboard with high power components. Assembly is straightforward and can be constructed by a beginner with access to soldering equipment. The cuvette chamber features a built-in enclosure with limited access to the power connectors as well as a removable lid. The lid can be 3D printed or laser cut from a sheet of acrylic or other material. 3D design and print files are available on this page. We chose a biodegradable and fire-resistant 3D print media,  Polylactic acid (PLA). Other cost effective, readily available, and more durable print media are available. The system was tested and performs as efficiently as a commercial electroporator.</p>
![](figs/Figure%202.3.png)


<p>2W (Watt)-1MΩ (Ohm) resistors were used for resistors R1-R2 and R9-R12. 8W-100kΩ resistors were used for resistors R3-R8.</p>
![](figs/Top view2.jpg)
<p>&nbsp;</p>
<p>Components were fixed to the breadboard using the long leads of resistors as traces on the underside of the 8cm x 12cm padboard.</p>
![](figs/Placement.PNG)
![](figs/bottom.png)
![](figs/Layout.png)

<p>Trimmed resistor terminals and solder were used to create traces. This layout accommodates the lack of premade traces found on solderless breadboards. In addition, banana jack connectors were soldered to the component side and traced to the opposing capacitor poles at each end of the bleed-down resistor array. This allows connection to a multimeter and real-time monitoring of the capacitor voltage during electroporation and provides assurance the capacitor is safe.</p>
<h2>
   <p>Enclosure</p>
</h2>
<p>We chose a commercially available plastic junction box to enclose our pulse generator circuit. A 13mm hole was drilled into the enclosure cover for the DPDT and 22mm holes were marked and drilled in the enclosure which provided a nice fit for the plastic NM connectors and pass-through cables.</p>
![](figs/encl.jpg)

<h4>
   <p>Assembly instruction</p>
</h4>
![](figs/encl%201.jpeg)
<p>Drill three 22mm holes in any side of the enclosure. Label the holes as shown. DMM above refers to digital multimeter.</p>
![](figs/encl%202.jpg)
<p>Drill 13mm hole in enclosure lid for switch mounting. Place the hole where hand-switching will be most comfortable.</p>
<p>&nbsp;</p>
<h3>
   <p>Switch wiring</p>
</h3>
<p>&nbsp;</p>
![](figs/pgen%20assmb%201.png)
<p>Cut 4 pieces of 18 AWG wire (for the switch) to 30cm lengths and strip approx. 5mm of bare wire from each end. Crimp one end of each wire to a ring terminal.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%202.1.jpg)
![](figs/pgen%20assmb%202.2.png)
<p>Attach ring terminals (with wire from step 1) to terminals 2, 3, 4, and 5 of the DPDT switch. Install switch into hole drilled into lid of case.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%203.jpg)
<p>Using the 4 pieces of 18 AWG wire with ring terminals from step 1, connect switch terminals 2 and 3 to the outboard ports of one terminal block and 4 and 5 to the outboard ports of another terminal block. Insert paired wires into outside wire cages of terminal blocks, then tighten terminal block screws.</p>
<p>&nbsp;</p>
<h2>
   <p>Cuvette Chamber</p>
</h2>
<p>The cuvette chamber provides the delivery vehicle for the electric field that causes electroporation. The cuvette chamber was designed to keep inward pressure on the plug ends that contact the cuvette. Hands-free electroporation was an important consideration in our design. The built-in spring-like nature of the resulting connection ensures constant contact when like charges build up on each plug and its corresponding cuvette contact. It is also notable that we chose stackable banana plugs so that we could tandem a 1,000V multimeter to the cuvette holder; especially useful during pre-electroporation functions check.</p>

<p>The cuvette chamber has several safety features. It is enclosed in a four-sided box with a removable lid that can be laser cut from a clear Poly acrylic sheet or 3D printed. Collars around lead connectors provide protection from shock exposure. Design and print files are included below. The chamber can be printed with various levels of fill; 15% fill is shown here and functioned well in our hands.</p>
![](figs/Gen2CHcollars.jpg)
![](figs/Gen2CHlid.jpg)
<p><strong>Print File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/Gen-2.1-with-edits/Enhanced%20Cuvette%20Chamber%203DPrintSTL.stl">Cuvette Chamber.stl</a></strong></p>
<p><strong>CAD Design File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/Gen-2.1-with-edits/Enhanced%20Cuvette%20Chamber%20CAD.dwg">Cuvette Chamber CAD.dwg</a></strong></p>
<p><strong>IGES File:&nbsp;<a href="https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/blob/Gen-2.1-with-edits/Dictyostelium%20discoideum%20Electroporator/Enclosure%20Lid%20FreeCAD.iges">Cuvette Chamber.iges</a></strong></p>

<p><strong>Chamber Lid Laser Cut File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/Gen-2.1-with-edits/Enclosure%20Lid%20LaserCutSVG.svg">Chamber Lid.SVG</a></strong></p>
<p><strong>Chamber Lid Print File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/Gen-2.1-with-edits/Enclosure%20Lid%20STL.stl">Chamber Lid STL.stl</a></strong></p>
<p><strong>Chamber Lid CAD Design File:&nbsp;<a href="https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/raw/Gen-2.1-with-edits/Enclosure%20Lid%20CAD.dwg">Chamber Lid CAD.dwg</a></strong></p>

<p><strong>Chamber Lid IGES File:&nbsp;<a href="https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/Dicty-Electroporator/Dicty-Electroporator.github.io/blob/Gen-2.1-with-edits/Dictyostelium%20discoideum%20Electroporator/Enhanced%20Cuvette%20Chamber%20FreeCAD.iges">Chamber Lid.iges</a></strong></p>
<p>Note: IGES drawing files save vector image data to transfer information between different CAD applications. Graphics acceleration may have to be disabled in order for some open source CAD software to load.</p>
<p>&nbsp;</p>
<h2>
   <p>Bill of Materials</p>
</h2>
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
            <p>Power supply banana plug test leads</p>
         </td>
         <td>
            <p>2</p>
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
            <p>Resistors - 8W-100kΩ</p>
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
            <p>Resistors - 2W-1MΩ</p>
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
            <p>Bio-Rad Model 3000xi Computer Controlled Electrophoresis Power Supply (or similar capable of generating at least 1KV DC)</p>
         </td>
         <td>
            <p>1</p>
         </td>
         <td>
            <p>ebay or other supplier of used scientific equipment</p>
         </td>
         <td>
            <p>    </p>
         </td>
         <td>
            <p><a href="https://www.ebay.com">www.ebay.com</a></p>
         </td>
      </tr>
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
         </td>
      </tr>
      <tr>
         <td>
            <p>3-Position Screw Terminal Block</p>
         </td>
         <td>
            <p>2</p>
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
            <p>Capacitor - 25μF - 1,300V</p>
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
            <p>10029</p>
         </td>
         <td>
            <p><a href="https://www.lowes.com/pd/CANTEX-Junction-Box-Gang-Gray-Plastic-Weatherproof-New-Work-Old-Work-Standard-Square-Interior-Exterior-Electrical-Box/3276255">www.lowes.com</a></p>
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
            <p>1kV Multimeter</p>
         </td>
         <td>
            <p>1</p>
         </td>
         <td>
            <p>CEN-TECH (or similar)</p>
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
            <p>Banana Jack Connector Standard Banana Solder Red/Black</p>
         </td>
         <td>
            <p>2</p>
         </td>
         <td>
            <p>Digi-Key</p>
         </td>
         <td>
            <p>3185-FCR7350R-ND (or similar)</p>
         </td>
         <td>
            <p><a href="https://www.digikey.com/en/products/detail/cliff-electronic-components-ltd/FCR7350R/13588710?utm_adgroup=Banana%20and%20Tip%20Connectors%20-%20Jacks%2C%20Plugs&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Connectors%2C%20Interconnects_NEW&utm_term=&utm_content=Banana%20and%20Tip%20Connectors%20-%20Jacks%2C%20Plugs&gclid=Cj0KCQjwxIOXBhCrARIsAL1QFCaS0i6JGg6UL4RwvlMztOWSG87LscZ9CT0JJhaYllfI620GVLvLvh8aAoXKEALw_wcB">www.digikey.com</a></p>
         </td>
         </tr>
            <tr>
         <td>
            <p>ISO-3864 Warning Symbol Labels - High Voltage</p>
         </td>
         <td>
            <p>1x5</p>
         </td>
         <td>
            <p>emedco</p>
         </td>
         <td>
            <p>SYM28R71VAD</p>
         </td>
         <td>
            <p><a href="https://www.emedco.com/iso-warning-symbol-labels-high-voltage-sym28.html?utm_campaign=PC-02-Labels_CatchAllSmartShopping_Emedco_PLA_NB_C_Google_US&utm_source=google&utm_medium=cpc&utm_term=&matchtype=&device=c&adgroupid=Catch+All+-+Old+Hierarchy&gclid=CjwKCAjwu5yYBhAjEiwAKXk_eOuXOPUcWMaTqpkfMpD0W6rF3nKtdNauUNZsvvMGXhg1-YWTsYK_4RoCVK8QAvD_BwE&gclsrc=aw.ds#SYM28R71VAD">www.emedco.com</a></p>
         </td>
         </tr>
   </tbody>
</table>

<p>&nbsp;</p> 
<h1>
   <p>Modular Pulse Generator</p>
</h1>
<p>Components and configurations of the electrical circuit are described here. For all connections, refer to the circuit diagram and photos of the assembled circuit.</p>
![](figs/pgen%20assemb%2011.png)
![](figs/Figure%202.3.png)


![](figs/pgen%20assmb%204.jpg)
<p>Clip resistor pins and bend at 90-degree angle to fit into breadboard terminals.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%205.jpg)
<p>Connect six 100KΩ - 2W resistors (R3-R8) in parallel into breadboards using jumper wires as needed to form connections.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%206.png)
<p>Connect two 1MΩ - 1/2W resistors (R1 and R2) in series into breadboards using jumper wires as needed to form connections.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%207.png)
<p>Connect four 1MΩ - 1/2W resistors (R9-R12) in series. A short jumper wire is also placed on the board as shown (upper left section of breadboard) that will become a link between the terminal blocks connecting switch position four and the cuvette chamber.</p>
<p>&nbsp;</p>
![](figs/pgen%20assmb%208.1.png)
![](figs/pgen%20assmb%208.2.jpg)
![](figs/pgen%20assemb%208.3.jpg)
<p>Ensure the 25μF - 1,300V capacitor is not charged before handling by measuring voltage across the terminals using the multimeter. Connect three 20cm flexible jumper wires to each pole of the capacitor. Note that two leads from each capacitor pole are present. Wire terminals can be crimped around capacitor leads or soldered for establishing a more permanent connection. Attach capacitor leads to the breadboard per circuit diagram and accompanying photos.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%209.1.jpg)
![](figs/pgen%20assemb%209.2.jpg)
<p>Connect terminal blocks from switch leads to the breadboard.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%2010.1.jpg)
![](figs/pgen%20assemb%2010.2.png)
<p>Cut one red and one black 60 in. test lead in half. Strip ends to leave approximately 5mm of bare wire. It might be helpful to tape the two pairs of one red and one black wire together every few centimeters. Pass stripped wire ends through NM plastic connectors about 10cm. Connect terminal blocks to the stripped ends by inserting paired wires into outside wire cages of terminal blocks, then tighten terminal block screws. Push NM plastic connectors into the cable pass-through holes of the enclosure (note that only two 22mm holes need to be made in the modular pulse generator enclosure, compared to three in the standard pulse generator enclosure).</p>
<p>&nbsp;</p>

<p>Pull the terminal block ends of the power supply and cuvette holder cables further through the pass-through holes with only sufficient play to insert the terminal blocks into the appropriate places on the breadboards.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%2012.png)
<p>Adhere the breadboards and capacitor to the inside base of the enclosure. While we used 2-sided tape, glue could be used for a more permanent solution. Connect power supply and cuvette holder terminal blocks to the breadboard.</p>
<p>&nbsp;</p>
![](figs/pgen%20assemb%2013.png)
<p>Attach enclosure cover.</p>
<p>&nbsp;</p>

<h2>
   <p>Bill of Materials</p>
</h2>
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
            <p>20601</p>
         </td>
         <td>
            <p><a href="[http://www.jameco.com](https://www.jameco.com/z/WBU-301-R-Jameco-Valuepro-400-Point-Solderless-Breadboard-3-3-Lx2-1-W_20601.html)">www.jameco.com</a></p>
         </td>
      </tr>
      <tr>
         <td>
            <p>Male-Male fixed length jumper wires</p>
         </td>
         <td>
            <p>1</p>
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
            <p>1</p>
         </td>
         <td>
            <p>Walmart</p>
         </td>
         <td>
            <p>NA</p>
         </td>
         <td>
            <p><a href="[https://www.mouser.com/ProductDetail/BusBoard-Prototype-Systems/KIT-ZWx4?qs=sGAEpiMZZMvh1pRuiUVjFZ0aAJXGPyuNDJiA5Z8ZR2Q%2FfInvTU3aKA%3D%3D](https://www.walmart.com/ip/Jumpers-Wire-Kit-Breadboard-Jumper-Assorted-Length-Brass-Wire-Core-Durable-For-Connecting-Electronic-Components/1240167396?wmlspartner=wlpa&selectedSellerId=101092147)">www.walmart.com</a></p>
         </td>
      </tr>
      <tr>
         <td>
            <p>Capacitor - 25μF - 1,300V</p>
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
            <p>Resistor - 1MΩ - 500mW</p>
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
            <p>Resistor - 100kΩ - 2W</p>
         </td>
         <td>
            <p>6</p>
         </td>
         <td>
            <p>Mouser</p>
         </td>
         <td>
            <p>603-MFR200FRF52-100K</p>
         </td>
         <td>
            <p><a href="[https://www.amazon.com/BAEASU-60PCS-Metal-Film-Resistor/dp/B07VCDJR8W?th=1](https://www.mouser.com/ProductDetail/YAGEO/MFR200FRF52-100K?qs=sGAEpiMZZMtlubZbdhIBIOunD5kldQoz6RmiTa0f1D8%3D)">www.mouser.com</a></p>
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
            <p>10029</p>
         </td>
         <td>
            <p><a href="[https://www.lowes.com/pd/CARLON-Gray-Weatherproof-Pvc-Junction-Box/1000975650](https://www.lowes.com/pd/CARLON-Gray-Weatherproof-Pvc-Junction-Box/1000975650)">www.lowes.com</a></p>
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
<h2>
   <p>Authors</p>
</h2>
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
