# mac_16bit

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>16-Bit MAC Unit Design</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }
        header {
            text-align: center;
            background: #0056b3;
            color: #fff;
            padding: 10px 0;
        }
        header h1 {
            margin: 0;
        }
        .section {
            margin-bottom: 20px;
	    text-align: center;
        }
        .section img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px auto;
        }
        .section h2 {
            color: #0056b3;
	    
        }
        footer {
            text-align: center;
            background: #333;
            color: #fff;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>16-Bit MAC Unit Design</h1>
            <p><strong>Technologies:</strong> Verilog, Cadence Tools (Genus, Innovus), Vedic Multipliers, CSA</p>
        </header>

        <section class="section">
            <h2>Overview</h2>
            <p>
                This project focuses on designing a high-performance 16-bit Multiply-Accumulate (MAC) unit. 
                The design utilizes Vedic multiplication techniques for fast computation and optimized addition 
                through Carry Save Adders (CSA). The implementation targets enhanced performance metrics such as 
                minimized delay, area, and power consumption.
            </p>
            <img src="RIFFh�" alt="Project Overview">

        </section>

        <section class="section">
            <h2>Design Methodology</h2>
            <p>
                The project employed the following steps: 
            </p>
            <ol>
                <li>
                    <strong>Vedic Multiplication</strong>: Leveraged the Urdhva Tiryakbhyam sutra for high-speed multiplication, 
                    breaking the computation into smaller modules (4-bit multipliers).
                </li>
                <li>
                    <strong>Optimized Addition</strong>: Used Carry Save Adders (CSA) to reduce propagation delay in the accumulation process.
                </li>
                <li>
                    <strong>RTL Implementation</strong>: Developed the Verilog code to integrate the modules.
                </li>
                <li>
                    <strong>Synthesis and Physical Design</strong>: Utilized Cadence tools:
                    <ul>
                        <li><strong>Genus</strong>: For RTL synthesis, constraint handling, and timing optimization.</li>
                        <li><strong>Innovus</strong>: For place and route, clock tree synthesis, and final GDSII file generation.</li>
                    </ul>
                </li>
            </ol>
            <img src="C:\Users\admin\OneDrive\Desktop\git hub pages\DALL·E 2024-12-09 10.39.49 - A detailed technical illustration showing the design methodology of a 16-bit Multiply-Accumulate (MAC) unit. The image should include labeled blocks f.webp" alt="Design Methodology">
        </section>

        <section class="section">
            <h2>Tools and Technologies</h2>
            <ul>
                <li><strong>Languages:</strong> Verilog HDL</li>
                <li><strong>EDA Tools:</strong> Cadence Genus (Synthesis), Cadence Innovus (Physical Design)</li>
                <li><strong>Mathematical Techniques:</strong> Vedic Multiplication, Carry Save Adder</li>
            </ul>
            <img src="C:\Users\admin\OneDrive\Desktop\git hub pages\tools and technologies.webp" alt="Tools and Technologies">
        </section>

        <section class="section">
            <h2>Results</h2>
            <p>
                The project achieved the following results:
            </p>
            <ul>
                <li>Optimized delay, area, and power consumption.</li>
                <li>Efficient multiplication and accumulation for 16-bit inputs.</li>
                <li>Final GDSII file generation with complete physical design.</li>
            </ul>
            <img src="C:\Users\admin\OneDrive\Desktop\git hub pages\results obtained.webp" alt="Project Results">
        </section>

        <footer>
            <p>&copy; 2024 Rohith Kumar. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
