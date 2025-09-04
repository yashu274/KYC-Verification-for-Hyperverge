# KYC-Verification-for-Hyperverge
This GitHub repository contains the code for a zero-dependency, single-page website built with HTML and Tailwind CSS. The site serves as a marketing landing page for Hyperverge, promoting its AI-powered, RBI-compliant Video KYC solution.
  <!-- ==========================================================
    CONTENT PLAN (text-only) — For SEO & alignment
    ----------------------------------------------------------
    HOMEPAGE (/)
    H1: The Future of Secure and Seamless Customer Onboarding is Here: Video KYC by Hyperverge
    Sub: Onboard customers in minutes... RBI-compliant, AI-powered...
    CTAs: Request a Demo (primary), Learn More (secondary)
    Why Choose: Security & Compliance | Efficiency & Cost Reduction | Customer Experience
    Trust: Client logos, badges, testimonial snippet
    Final CTA: Get Started Today

    HOW IT WORKS (/how-it-works)
    H1: Our Simple 4-Step Video KYC Process
    Steps: Pre-qualification | Smart Queuing | The Video Call | Post-call Analytics

    FEATURES (/features)
    H1: Powered by Cutting-Edge Technology
    Columns: AI & ML (Liveness, Face Match~99%, OCR), Seamless Integration (APIs/SDKs, uptime, support)
    Trust Signals: Compliance badges, testimonials, client logos

    INDUSTRIES (/industries)
    H1: Built for Regulated Industries
    Banking | Fintech & NBFC (tailored benefit copy)

    ABOUT US (/about-us)
    Mission/vision paragraph focused on trust, speed, compliance at scale.

    RESOURCES (/resources)
    Webinar embed, case study PDF, blog post cards

    CONTACT (/contact)
    Form fields: Name, Company, Email, Phone, Industry, Message

    REQUEST DEMO (/request-demo)
    Expanded lead form with Preferred Time and SLA promise

    SEO KEYWORDS (sprinkled naturally):
    video kyc, rbi compliant kyc, kyc compliance, ai kyc, liveness detection, face match, fintech onboarding, digital onboarding, fraud detection, ekyc, kyc solution for banks
  =========================================================== -->

  <!-- ==========================================================
    IMAGE SUGGESTIONS / PROMPTS
    ----------------------------------------------------------
    Hero: "Professional agent on a video call with a smiling customer; subtle overlay of shield/lock/dataflow icons; modern office; shallow depth of field"
    Tech/AI: "Abstract neural network lines forming a shield; dark navy background with electric blue accents"
    Compliance: "Minimal badge icons for RBI/ISO/DPDP on clean light background"
    Industries: "Bank branch UI, mobile banking app screens; fintech office team collaborating"
    Avoid generic stock; aim for aspirational, tech-forward visuals.
  =========================================================== -->

  <!-- ==========================================================
    DEPLOYMENT & MANAGEMENT NOTES
    ----------------------------------------------------------
    • This file is a zero-dependency SPA using Tailwind CDN. For production:
      1) Move to a framework (Next.js/Vite) or precompile Tailwind for performance.
      2) Replace CDN with compiled CSS (Purged) to keep CSS <10KB.
      3) Add <link rel="canonical"> per route if using SSR; otherwise keep SPA and map hashes.
      4) Wire forms to a backend: POST /api/lead (Node, Python, or serverless). Validate server-side and send email to sales.
      5) Add security headers (CSP, X-Frame-Options), serve over HTTPS.
      6) Add Google Analytics (gtag) in <head> and track key events (CTA clicks, form submits).
      7) Replace webinar iframe src with your YouTube URL; upload case study PDFs and link.
      8) Configure sitemap.xml and robots.txt. Add OpenGraph/Twitter meta tags.

    • Quick hosting:
      - GitHub Pages / Netlify / Vercel: drop this index.html in a repo and deploy.
      - For hash routes, no server rewrites needed. If you migrate to clean paths, add rewrite rules.
  =========================================================== -->
