<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub README Logo - Path of Divine Truth</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1a1f36 0%, #0f1525 100%);
            color: #e8e8e8;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            width: 100%;
            background: rgba(18, 22, 40, 0.95);
            border-radius: 20px;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.6);
            overflow: hidden;
            border: 1px solid rgba(120, 130, 180, 0.15);
        }
        
        header {
            text-align: center;
            padding: 40px 30px;
            background: rgba(15, 18, 35, 0.85);
            border-bottom: 1px solid rgba(100, 120, 160, 0.15);
        }
        
        h1 {
            font-family: 'Georgia', serif;
            font-size: 2.8rem;
            color: #e0d0a0;
            margin-bottom: 15px;
        }
        
        .subtitle {
            font-size: 1.3rem;
            color: #b0c0d8;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .content {
            display: flex;
            flex-wrap: wrap;
            padding: 40px;
            gap: 40px;
        }
        
        .logo-section {
            flex: 1;
            min-width: 300px;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 30px;
            background: rgba(20, 25, 45, 0.5);
            border-radius: 15px;
        }
        
        .logo-display {
            width: 300px;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 30px;
        }
        
        .instructions {
            flex: 1;
            min-width: 300px;
            padding: 30px;
            background: rgba(20, 25, 45, 0.5);
            border-radius: 15px;
        }
        
        .section-title {
            font-family: 'Georgia', serif;
            font-size: 1.8rem;
            color: #e0d0a0;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 1px solid rgba(224, 208, 160, 0.2);
        }
        
        .steps {
            margin-bottom: 30px;
        }
        
        .step {
            margin-bottom: 25px;
            padding-left: 40px;
            position: relative;
        }
        
        .step-number {
            position: absolute;
            left: 0;
            top: 0;
            width: 30px;
            height: 30px;
            background: #e0d0a0;
            color: #1a1a2e;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-weight: bold;
            font-family: 'Courier New', monospace;
        }
        
        .step-title {
            font-size: 1.3rem;
            color: #e0d0a0;
            margin-bottom: 10px;
        }
        
        .step-content {
            font-size: 1.1rem;
            color: #d0d8e8;
            line-height: 1.7;
        }
        
        .code-block {
            background: rgba(15, 18, 35, 0.8);
            border-radius: 8px;
            padding: 20px;
            margin-top: 15px;
            font-family: 'Courier New', monospace;
            font-size: 0.95rem;
            line-height: 1.5;
            overflow-x: auto;
            border: 1px solid rgba(224, 208, 160, 0.2);
            position: relative;
        }
        
        .copy-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            padding: 5px 10px;
            background: rgba(224, 208, 160, 0.2);
            color: #e0d0a0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.9rem;
        }
        
        .copy-btn:hover {
            background: rgba(224, 208, 160, 0.3);
        }
        
        .preview {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: rgba(25, 30, 55, 0.4);
            border-radius: 10px;
        }
        
        .preview-title {
            font-size: 1.2rem;
            color: #e0d0a0;
            margin-bottom: 15px;
        }
        
        .github-preview {
            width: 200px;
            height: 200px;
            margin: 0 auto;
            background: #f0f0f0;
            border-radius: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        footer {
            text-align: center;
            padding: 30px;
            font-size: 1.1rem;
            color: #9cb3c9;
            background: rgba(12, 15, 30, 0.95);
            border-top: 1px solid rgba(100, 120, 160, 0.15);
        }
        
        @media (max-width: 768px) {
            .content {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2.3rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>GitHub README Logo</h1>
            <p class="subtitle">Add your Path of Divine Truth logo to your GitHub README.md</p>
        </header>
        
        <div class="content">
            <div class="logo-section">
                <h2 class="section-title">Your Logo</h2>
                <div class="logo-display">
                    <svg width="300" height="300" viewBox="0 0 300 300" xmlns="http://www.w3.org/2000/svg">
                        <!-- Background circle -->
                        <circle cx="150" cy="150" r="145" fill="#0f172a" stroke="#1e293b" stroke-width="1"/>
                        
                        <!-- Divine light rays -->
                        <g opacity="0.7">
                            <line x1="150" y1="0" x2="150" y2="100" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                            <line x1="150" y1="0" x2="120" y2="80" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                            <line x1="150" y1="0" x2="180" y2="80" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                            <line x1="150" y1="0" x2="100" y2="60" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                            <line x1="150" y1="0" x2="200" y2="60" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                        </g>
                        
                        <!-- Open Bible -->
                        <g transform="translate(80, 100)">
                            <!-- Left cover -->
                            <rect x="0" y="0" width="70" height="100" rx="3" fill="#2a210f"/>
                            <rect x="10" y="45" width="15" height="100" fill="#1a150a"/>
                            <text x="25" y="100" font-family="Georgia" font-size="12" fill="#e0d0a0" text-anchor="middle" transform="rotate(-90 25 100)">HOLY BIBLE</text>
                            
                            <!-- Pages -->
                            <rect x="70" y="5" width="60" height="90" rx="2" fill="#f8f4e0"/>
                            
                            <!-- Page lines -->
                            <g stroke="#000" stroke-opacity="0.1" stroke-width="1">
                                <line x1="75" y1="15" x2="125" y2="15"/>
                                <line x1="75" y1="25" x2="125" y2="25"/>
                                <line x1="75" y1="35" x2="125" y2="35"/>
                                <line x1="75" y1="45" x2="125" y2="45"/>
                                <line x1="75" y1="55" x2="125" y2="55"/>
                                <line x1="75" y1="65" x2="125" y2="65"/>
                                <line x1="75" y1="75" x2="125" y2="75"/>
                                <line x1="75" y1="85" x2="125" y2="85"/>
                            </g>
                            
                            <!-- Scripture text -->
                            <text x="100" y="30" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle">"Your word is a lamp</text>
                            <text x="100" y="40" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle">to my feet and a light</text>
                            <text x="100" y="50" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle">to my path."</text>
                            <text x="100" y="65" font-family="Georgia" font-size="7" fill="#555" text-anchor="middle">- Psalm 119:105</text>
                        </g>
                        
                        <!-- Divine path -->
                        <path d="M 50 230 Q 150 180 250 230" stroke="#e0d0a0" stroke-width="6" fill="none"/>
                    </svg>
                </div>
                <p style="color: #b0c0d8; text-align: center; max-width: 300px;">
                    This SVG logo will maintain its quality at any size and is perfect for GitHub README files.
                </p>
            </div>
            
            <div class="instructions">
                <h2 class="section-title">Add to GitHub README</h2>
                
                <div class="steps">
                    <div class="step">
                        <div class="step-number">1</div>
                        <div class="step-title">Copy the SVG Code</div>
                        <div class="step-content">
                            Copy the following SVG code to your clipboard:
                        </div>
                        <div class="code-block" id="svg-code">
                            <button class="copy-btn" onclick="copySVGCode()">Copy</button>
                            <pre><code>&lt;svg width="300" height="300" viewBox="0 0 300 300" xmlns="http://www.w3.org/2000/svg"&gt;
  &lt;circle cx="150" cy="150" r="145" fill="#0f172a" stroke="#1e293b" stroke-width="1"/&gt;
  
  &lt;g opacity="0.7"&gt;
    &lt;line x1="150" y1="0" x2="150" y2="100" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/&gt;
    &lt;line x1="150" y1="0" x2="120" y2="80" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/&gt;
    &lt;line x1="150" y1="0" x2="180" y2="80" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/&gt;
    &lt;line x1="150" y1="0" x2="100" y2="60" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/&gt;
    &lt;line x1="150" y1="0" x2="200" y2="60" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/&gt;
  &lt;/g&gt;
  
  &lt;g transform="translate(80, 100)"&gt;
    &lt;rect x="0" y="0" width="70" height="100" rx="3" fill="#2a210f"/&gt;
    &lt;rect x="10" y="45" width="15" height="100" fill="#1a150a"/&gt;
    &lt;text x="25" y="100" font-family="Georgia" font-size="12" fill="#e0d0a0" text-anchor="middle" transform="rotate(-90 25 100)"&gt;HOLY BIBLE&lt;/text&gt;
    
    &lt;rect x="70" y="5" width="60" height="90" rx="2" fill="#f8f4e0"/&gt;
    
    &lt;g stroke="#000" stroke-opacity="0.1" stroke-width="1"&gt;
      &lt;line x1="75" y1="15" x2="125" y2="15"/&gt;
      &lt;line x1="75" y1="25" x2="125" y2="25"/&gt;
      &lt;line x1="75" y1="35" x2="125" y2="35"/&gt;
      &lt;line x1="75" y1="45" x2="125" y2="45"/&gt;
      &lt;line x1="75" y1="55" x2="125" y2="55"/&gt;
      &lt;line x1="75" y1="65" x2="125" y2="65"/&gt;
      &lt;line x1="75" y1="75" x2="125" y2="75"/&gt;
      &lt;line x1="75" y1="85" x2="125" y2="85"/&gt;
    &lt;/g&gt;
    
    &lt;text x="100" y="30" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle"&gt;"Your word is a lamp&lt;/text&gt;
    &lt;text x="100" y="40" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle"&gt;to my feet and a light&lt;/text&gt;
    &lt;text x="100" y="50" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle"&gt;to my path."&lt;/text&gt;
    &lt;text x="100" y="65" font-family="Georgia" font-size="7" fill="#555" text-anchor="middle"&gt;- Psalm 119:105&lt;/text&gt;
  &lt;/g&gt;
  
  &lt;path d="M 50 230 Q 150 180 250 230" stroke="#e0d0a0" stroke-width="6" fill="none"/&gt;
&lt;/svg&gt;</code></pre>
                        </div>
                    </div>
                    
                    <div class="step">
                        <div class="step-number">2</div>
                        <div class="step-title">Paste into README.md</div>
                        <div class="step-content">
                            Paste the SVG code directly into your GitHub README.md file. You can:
                            <ul style="margin-top: 10px; margin-left: 20px;">
                                <li>Place it at the top for a logo header</li>
                                <li>Center it using HTML div tags</li>
                                <li>Resize it by adjusting the width and height attributes</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="step">
                        <div class="step-number">3</div>
                        <div class="step-title">Center the Logo (Optional)</div>
                        <div class="step-content">
                            To center the logo in your README, wrap it in div tags:
                        </div>
                        <div class="code-block">
                            <pre><code>&lt;div align="center"&gt;
  &lt;!-- SVG CODE HERE --&gt;
&lt;/div&gt;</code></pre>
                        </div>
                    </div>
                </div>
                
                <div class="preview">
                    <div class="preview-title">GitHub Preview</div>
                    <div class="github-preview">
                        <svg width="150" height="150" viewBox="0 0 300 300" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="150" cy="150" r="145" fill="#0f172a" stroke="#1e293b" stroke-width="1"/>
                            
                            <g opacity="0.7">
                                <line x1="150" y1="0" x2="150" y2="100" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                                <line x1="150" y1="0" x2="120" y2="80" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                                <line x1="150" y1="0" x2="180" y2="80" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                                <line x1="150" y1="0" x2="100" y2="60" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                                <line x1="150" y1="0" x2="200" y2="60" stroke="#f9f5e5" stroke-width="4" stroke-linecap="round"/>
                            </g>
                            
                            <g transform="translate(80, 100)">
                                <rect x="0" y="0" width="70" height="100" rx="3" fill="#2a210f"/>
                                <rect x="10" y="45" width="15" height="100" fill="#1a150a"/>
                                <text x="25" y="100" font-family="Georgia" font-size="12" fill="#e0d0a0" text-anchor="middle" transform="rotate(-90 25 100)">HOLY BIBLE</text>
                                
                                <rect x="70" y="5" width="60" height="90" rx="2" fill="#f8f4e0"/>
                                
                                <g stroke="#000" stroke-opacity="0.1" stroke-width="1">
                                    <line x1="75" y1="15" x2="125" y2="15"/>
                                    <line x1="75" y1="25" x2="125" y2="25"/>
                                    <line x1="75" y1="35" x2="125" y2="35"/>
                                    <line x1="75" y1="45" x2="125" y2="45"/>
                                    <line x1="75" y1="55" x2="125" y2="55"/>
                                    <line x1="75" y1="65" x2="125" y2="65"/>
                                    <line x1="75" y1="75" x2="125" y2="75"/>
                                    <line x1="75" y1="85" x2="125" y2="85"/>
                                </g>
                                
                                <text x="100" y="30" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle">"Your word is a lamp</text>
                                <text x="100" y="40" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle">to my feet and a light</text>
                                <text x="100" y="50" font-family="Georgia" font-size="8" fill="#333" text-anchor="middle">to my path."</text>
                                <text x="100" y="65" font-family="Georgia" font-size="7" fill="#555" text-anchor="middle">- Psalm 119:105</text>
                            </g>
                            
                            <path d="M 50 230 Q 150 180 250 230" stroke="#e0d0a0" stroke-width="6" fill="none"/>
                        </svg>
                    </div>
                    <p style="color: #b0c0d8; margin-top: 15px;">
                        This is how your logo will appear in a GitHub README
                    </p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>Path of Divine Truth Logo | Created for GitHub README</p>
            <p>Inspired by Psalm 119:105 | "Your word is a lamp to my feet and a light to my path"</p>
        </footer>
    </div>
    
    <script>
        function copySVGCode() {
            const codeElement = document.querySelector('#svg-code code');
            const textArea = document.createElement('textarea');
            textArea.value = codeElement.textContent;
            document.body.appendChild(textArea);
            textArea.select();
            document.execCommand('copy');
            document.body.removeChild(textArea);
            
            const copyButton = document.querySelector('#svg-code .copy-btn');
            copyButton.textContent = 'Copied!';
            setTimeout(() => {
                copyButton.textContent = 'Copy';
            }, 2000);
        }
    </script>
</body>
</html>
