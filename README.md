# testing
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stop Losing Sales - Master the Art of Client Connection in 90 Days</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }
        
        .preheader {
            text-align: center;
            background-color: #e74c3c;
            color: white;
            padding: 10px;
            font-weight: bold;
            margin-bottom: 0;
        }
        
        .hero {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            margin-bottom: 0;
        }
        
        .hero h1 {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero h2 {
            font-size: 1.3em;
            margin-bottom: 30px;
            font-weight: normal;
            opacity: 0.9;
        }
        
        .vsl-container {
            margin: 30px 0;
        }
        
        .vsl-icon {
            display: inline-block;
            position: relative;
            background: #000;
            padding: 20px 40px;
            border-radius: 10px;
            cursor: pointer;
            transition: transform 0.3s ease;
            text-decoration: none;
            color: white;
        }
        
        .vsl-icon:hover {
            transform: scale(1.05);
        }
        
        .play-button {
            width: 60px;
            height: 60px;
            background: #e74c3c;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 15px;
            position: relative;
        }
        
        .play-button::after {
            content: '';
            width: 0;
            height: 0;
            border-left: 20px solid white;
            border-top: 12px solid transparent;
            border-bottom: 12px solid transparent;
            margin-left: 5px;
        }
        
        .vsl-text {
            font-size: 1.1em;
            font-weight: bold;
        }
        
        .cta-primary {
            background-color: #e74c3c;
            color: white;
            padding: 18px 40px;
            font-size: 1.2em;
            font-weight: bold;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
            transition: background-color 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }
        
        .cta-primary:hover {
            background-color: #c0392b;
        }
        
        .section {
            padding: 40px 20px;
            margin-bottom: 0;
        }
        
        .section h2 {
            font-size: 2em;
            margin-bottom: 25px;
            color: #2c3e50;
            text-align: center;
        }
        
        .section p {
            font-size: 1.1em;
            margin-bottom: 15px;
            max-width: 2-3 sentences per paragraph;
        }
        
        .highlight {
            background-color: #fff3cd;
            padding: 20px;
            border-left: 5px solid #ffc107;
            margin: 20px 0;
            font-style: italic;
        }
        
        .bullet-point {
            background-color: #f8f9fa;
            padding: 15px;
            margin: 15px 0;
            border-left: 4px solid #667eea;
        }
        
        .bullet-point strong {
            color: #2c3e50;
        }
        
        .testimonial {
            background-color: #e8f5e8;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            font-style: italic;
            text-align: center;
        }
        
        .faq {
            background-color: #f1f3f4;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
        }
        
        .faq h4 {
            color: #2c3e50;
            margin-bottom: 10px;
            font-size: 1.1em;
        }
        
        .price-strike {
            text-decoration: line-through;
            color: #999;
            font-size: 1.2em;
        }
        
        .price-current {
            color: #e74c3c;
            font-size: 2em;
            font-weight: bold;
        }
        
        .urgency {
            background-color: #ffe6e6;
            padding: 15px;
            border: 2px solid #e74c3c;
            margin: 20px 0;
            text-align: center;
            border-radius: 8px;
        }
        
        .guarantee {
            background-color: #e8f5e8;
            padding: 20px;
            border: 2px solid #28a745;
            margin: 20px 0;
            text-align: center;
            border-radius: 8px;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 1.8em;
                line-height: 1.3;
            }
            
            .hero h2 {
                font-size: 1.1em;
                line-height: 1.4;
            }
            
            .container {
                padding: 5px;
                margin: 0;
            }
            
            .section {
                padding: 25px 15px;
            }
            
            .section h2 {
                font-size: 1.5em;
                line-height: 1.3;
            }
            
            .cta-primary {
                padding: 15px 25px;
                font-size: 1.1em;
                width: 100%;
                max-width: 300px;
            }
            
            .vsl-icon {
                padding: 15px 25px;
                width: 100%;
                max-width: 280px;
            }
            
            .play-button {
                width: 50px;
                height: 50px;
            }
            
            .play-button::after {
                border-left: 15px solid white;
                border-top: 10px solid transparent;
                border-bottom: 10px solid transparent;
            }
            
            .bullet-point, .faq, .highlight, .testimonial, .guarantee, .urgency {
                margin: 15px 0;
                padding: 15px;
            }
        }
        
        @media (max-width: 480px) {
            .hero h1 {
                font-size: 1.5em;
            }
            
            .hero h2 {
                font-size: 1em;
            }
            
            .section h2 {
                font-size: 1.3em;
            }
            
            .hero {
                padding: 30px 15px;
            }
            
            .preheader {
                font-size: 0.9em;
                padding: 8px;
            }
        }
    </style>
</head>
<body>
    <!-- PREHEADER -->
    <div class="preheader">
        SALES PROFESSIONALS, TEAM LEADERS & SMALL BUSINESS OWNERS
    </div>

    <div class="container">
        <!-- HERO SECTION -->
        <div class="hero">
            <h1>Stop Losing Sales to Competitors Who Sound Exactly Like You</h1>
            <h2>Master the client connection system that closes 73% more deals in 90 days... without pushy scripts or fake enthusiasm</h2>
            
            <div class="vsl-container">
                <a href="https://docs.google.com/document/d/12LNyJAkyYIPKd0_xfiHF_M8emjB2xkCUyQB4x5LI7Ew/edit?usp=sharing" class="vsl-icon">
                    <div class="play-button"></div>
                    <div class="vsl-text">Click Here To See The: VSL I WROTE FOR YOU</div>
                </a>
            </div>
            
            <a href="https://majoydacia.com/" class="cta-primary">Book Your FREE Strategy Call Now</a>
        </div>

        <!-- PROBLEM IDENTIFICATION -->
        <div class="section">
            <h2>The Harsh Truth About Why Your Sales Are Stuck</h2>
            
            <p>You walk into that meeting confident...</p>
            
            <p>You've rehearsed your pitch. You know your product inside and out. You're ready to close.</p>
            
            <p>But 20 minutes later, you're watching another potential client "think about it" — which really means they're calling your competitor.</p>
            
            <p><strong>Sound familiar?</strong></p>
            
            <p>Maybe you've spent thousands on sales training programs that taught you to "follow up seven times" and "always be closing."</p>
            
            <p>Perhaps you've memorized objection-handling scripts that make you sound like a telemarketing robot.</p>
            
            <p>Or you've tried those "miracle" sales courses promising instant results... only to find yourself still struggling to hit your targets month after month.</p>
            
            <p>Here's what's really happening...</p>
            
            <p>While you're reciting the same generic sales playbook as everyone else, your prospects are getting MORE sophisticated at filtering out salespeople.</p>
            
            <p>They can smell a cookie-cutter approach from miles away.</p>
            
            <p><strong>And every day you stick with these outdated methods, you're hemorrhaging potential income.</strong></p>
            
            <p>But what if I told you there's a completely different approach — one that 96% of salespeople have never heard of?</p>
        </div>

        <!-- ORIGIN STORY -->
        <div class="section">
            <h2>How I Went From Struggling Telemarketer to Sales Coach for 9 Countries</h2>
            
            <p>Twenty-five years ago, I was exactly where you are now.</p>
            
            <p>Frustrated. Inconsistent results. Watching "natural born salespeople" close deals while I struggled to book appointments.</p>
            
            <p>I had tried everything...</p>
            
            <p>High-energy sales seminars where everyone got pumped up for three days, then went back to the same mediocre results.</p>
            
            <p>Expensive sales systems that promised to "automate" my success.</p>
            
            <p>Even hired a personal sales coach who gave me the same tired advice about "believing in my product."</p>
            
            <p><strong>Then something changed everything.</strong></p>
            
            <p>I was about to lose my biggest client. My retention rates were terrible. People would buy once, then disappear.</p>
            
            <p>That's when I realized the fatal flaw in everything I'd been taught...</p>
            
            <p>Every sales method focuses on what YOU want (the sale), not what THEY need (to feel understood).</p>
            
            <p>So I started studying something completely different: human psychology and relationship dynamics.</p>
            
            <p>Not sales psychology — actual behavioral science.</p>
            
            <p>And I made a discovery that changed everything...</p>
            
            <p>People don't buy from salespeople. They buy from people who genuinely understand their world.</p>
        </div>

        <!-- SOLUTION REVELATION -->
        <div class="section">
            <h2>The "Client Connection System" That Makes Selling Feel Natural</h2>
            
            <p>After years of testing and refining across 9 different countries and dozens of industries, I developed what I call the Client Connection System.</p>
            
            <p>This isn't about learning new scripts or sales techniques.</p>
            
            <p><strong>It's about becoming the type of person clients WANT to buy from.</strong></p>
            
            <p>Here's how it works...</p>
            
            <div class="bullet-point">
                <strong>Deep Client Mapping:</strong> You learn to read people's true motivations in the first 5 minutes of conversation, so you speak directly to their core desires instead of surface-level needs.
            </div>
            
            <div class="bullet-point">
                <strong>Invisible Influence Techniques:</strong> Position yourself as the trusted advisor who solves problems, not another salesperson pushing products — making price objections virtually disappear.
            </div>
            
            <div class="bullet-point">
                <strong>The Retention Multiplier:</strong> Create such strong client relationships that 85% of your business comes from repeat customers and referrals — no more cold calling treadmill.
            </div>
            
            <div class="bullet-point">
                <strong>Industry-Specific Customization:</strong> Whether you're in B2B, retail, hospitality, or telemarketing, you get strategies tailored to YOUR exact situation and market.
            </div>
            
            <p>The results speak for themselves...</p>
            
            <p>Clients consistently report 40-70% increases in closing rates within 90 days.</p>
            
            <p>More importantly, they feel confident and natural during sales conversations — no more pushy, desperate energy.</p>
            
            <p><strong>Because when you truly connect with people, selling becomes effortless.</strong></p>
        </div>

        <!-- PRODUCT INTRODUCTION -->
        <div class="section">
            <h2>Finally... Personalized Sales Coaching That Actually Works</h2>
            
            <p>After 25 years of helping sales professionals across the Philippines, Singapore, Thailand, Malaysia, Indonesia, Cambodia, Japan, Australia, and the USA, I've decided to make my proven system available to a select group of serious professionals.</p>
            
            <p><strong>Introducing: The Majoy Dacia Sales Mastery Program</strong></p>
            
            <p>This isn't another one-size-fits-all course you'll watch once and forget.</p>
            
            <p>This is completely personalized coaching designed around YOUR specific challenges, industry, and goals.</p>
            
            <div class="bullet-point">
                <strong>One-on-One Strategy Sessions:</strong> We work together to identify your unique selling obstacles and create a custom plan that fits your personality and market.
            </div>
            
            <div class="bullet-point">
                <strong>Industry-Specific Training:</strong> Whether you need telemarketing mastery, face-to-face selling excellence, or team leadership skills — you get exactly what you need, nothing you don't.
            </div>
            
            <div class="bullet-point">
                <strong>Real-World Application:</strong> No theory or fluff — just practical techniques you can use in your very next client conversation.
            </div>
            
            <div class="bullet-point">
                <strong>Ongoing Support System:</strong> Access to weekly workshops, YouTube training library, and a community of like-minded professionals for continued growth.
            </div>
            
            <p>Unlike generic sales training that treats every industry the same, this program adapts to YOUR specific situation.</p>
            
            <p>Telemarketer struggling with objections? You get specialized cold-calling strategies.</p>
            
            <p>Team leader with underperforming staff? You get leadership techniques that motivate without micromanaging.</p>
            
            <p>Small business owner bleeding customers? You get retention systems that turn one-time buyers into lifelong advocates.</p>
        </div>

        <!-- OFFER STRUCTURE -->
        <div class="section">
            <h2>Everything You Need to Dominate Your Market</h2>
            
            <p>When you work with me, you're not just getting coaching — you're getting a complete transformation system:</p>
            
            <div class="bullet-point">
                <strong>Free Initial Strategy Consultation:</strong> We analyze your current situation and create a custom roadmap for your success — worth $500, yours free.
            </div>
            
            <div class="bullet-point">
                <strong>Personalized Training Program:</strong> Choose from Sales Skills, Communication Mastery, Telemarketing Excellence, Objection Handling, Cold Calling, Face-to-Face Selling, Team Leadership, Customer Service, or Appointment Setting — all customized to your needs.
            </div>
            
            <div class="bullet-point">
                <strong>YouTube Training Library:</strong> Exclusive access to 247 training videos, including the viral "23 minutes of SALES TRAINING that will Explode Your Sales in 2025" — continuously updated with fresh content.
            </div>
            
            <div class="bullet-point">
                <strong>Weekly Live Workshops:</strong> Join small group sessions for ongoing learning and networking with other high-performing professionals.
            </div>
            
            <div class="bullet-point">
                <strong>Referral Rewards Program:</strong> Earn $100 SGD credit for every qualified referral — because successful people know successful people.
            </div>
            
            <div class="guarantee">
                <h3>My Personal Success Guarantee</h3>
                <p>I'm so confident in this system that I personally guarantee your results. If you don't see measurable improvement in your sales performance within 90 days of implementing my strategies, I'll work with you until you do — at no additional cost.</p>
            </div>
            
            <div class="urgency">
                <p><strong>IMPORTANT:</strong> Due to the personalized nature of this program, I can only work with 12 new clients this quarter. 7 spots have already been claimed by referrals.</p>
            </div>
            
            <a href="https://majoydacia.com/" class="cta-primary">Claim Your FREE Strategy Session Now</a>
        </div>

        <!-- FAQ SECTION -->
        <div class="section">
            <h2>Your Questions Answered</h2>
            
            <div class="faq">
                <h4>Q: "How is this different from other sales training programs?"</h4>
                <p>Most programs give you generic scripts and techniques. I give you personalized strategies based on YOUR industry, personality, and specific challenges. Plus, you're learning from someone who's actually sold in 9 different countries — not just taught theory.</p>
            </div>
            
            <div class="faq">
                <h4>Q: "Will this work in my specific industry?"</h4>
                <p>Absolutely. I've worked across hospitality, retail, B2B, B2C, telemarketing, and more. The Client Connection System adapts to any industry because it's based on human psychology, not product features. During our free consultation, I'll show you exactly how it applies to your market.</p>
            </div>
            
            <div class="faq">
                <h4>Q: "I'm already successful. Can this help me reach the next level?"</h4>
                <p>If you're successful but hitting a plateau, this is perfect for you. Most high-performers struggle with two things: scaling beyond personal effort and building systems that work without them. The advanced strategies I teach are designed specifically for professionals ready to dominate their market completely.</p>
            </div>
            
            <div class="faq">
                <h4>Q: "How much time does this require?"</h4>
                <p>The beauty of personalized coaching is efficiency. Instead of wasting months on irrelevant techniques, you focus only on what moves the needle for YOU. Most clients see significant improvements with just 2-3 hours per week of focused implementation.</p>
            </div>
            
            <div class="faq">
                <h4>Q: "What if I'm not good at implementing new strategies?"</h4>
                <p>That's exactly why this is personalized. I don't give you a generic course and wish you luck. We work together to ensure you're implementing correctly. Plus, with weekly workshops and ongoing support, you're never alone in the process.</p>
            </div>
            
            <p style="text-align: center; font-size: 1.2em; margin-top: 40px;"><strong>Ready to become the salesperson everyone wants to buy from?</strong></p>
            
            <a href="https://majoydacia.com/" class="cta-primary">Book Your FREE Strategy Call Now</a>
        </div>
    </div>
</body>
</html>
