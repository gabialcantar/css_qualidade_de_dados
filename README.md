.sec-1 .container,
.sec-2 .container,
.sec-3 .container,
.sec-4 .container,
.sec-5 .container,
.sec-7 .container {
    display: flex;
    flex-wrap: wrap;
}
.sec-1,
.sec-2,
.sec-3,
.sec-4,
.sec-5,
.sec-7 { 
display: flex; 
flex-wrap: wrap;
min-height: auto; 
}
.section-clip {
clip-path: polygon(0 0, 100% 0, 100% 92%, 0 100%); 
} 

/* HERO */ 
.hero-content { 
flex-grow: 1;
display: flex;
flex-direction: column;
align-items: center;
text-align: center;
padding: 56px 40px;
}

.hero-title {
font-size: clamp(1.8rem, 4vw, 2.8rem); 
font-weight: 800;
color: #000;
margin-bottom: 12px;
}

.hero-text {
color: rgba(0, 0, 0, .85);
font-size: 1.05rem;
max-width: 520px; 
line-height: 1.7; 
} 

/* TÍTULOS */
.section-label { 
font-size: .72rem; 
letter-spacing: .18em;
text-transform: uppercase;
font-weight: 600;
display: block;
margin-bottom: 10px;
}

.section-label.dark {
color: rgba(0, 0, 0, .75);
}

.section-label.light { 
color: rgba(0, 0, 0, 0.75); 
} 

.section-title { 
font-size: clamp(1.5rem, 3vw, 2.2rem);
font-weight: 700;
margin-bottom: 16px; 
}

.section-title.light {
color: #000000;
}

.section-title.dark {
color: #000;
}

.section-text {
line-height: 1.7;
padding: 8px 0; 
}

.section-text.light {
color: rgba(0, 0, 0, 0.85);
}

.section-text.dark {
color: rgba(0, 0, 0, .85);
}

.center {
max-width: 520px;
margin: 0 auto;
}

/* COLUNAS */
.content-column,
.image-column {
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 64px 40px;
}
.section-content {
flex-grow: 1;
display: flex;
flex-direction: column;
padding: 64px 40px;
}

/* IMAGENS */
.section-image {
width: 100%;
height: auto;
border-radius: 20px;
box-shadow: 0 20px 56px rgba(0,0,0,.2);
}

/* BOTÕES */
.custom-btn {
    background: #000;
    color: #fff !important;
    border: none;
    border-radius: 999px;
    padding: 14px 30px;
    font-weight: 700;
    font-size: 1rem;
    cursor: pointer;
    margin-top: 8px;
    display: inline-block;
    text-decoration: none;
    text-align: center;
}

.custom-btn:hover,
.custom-btn:focus,
.custom-btn:active {
    background: #000 !important;
    color: #fff !important;
    text-decoration: none;
}

/* BENEFÍCIOS */
.section-header {
text-align: center;
margin-bottom: 48px;
}

.cards-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
gap: 24px; }
.benefit-card {
background: rgba(255,255,255,.70);
border-radius: 20px;
padding: 32px;
} 

.card-icon {
width: 48px;
height: 48px;
border-radius: 14px;
background: var(--brand);
display: flex;
align-items: center;
justify-content: center;
font-size: 1.4rem;
margin-bottom: 20px;
}

.benefit-card h3 {
font-size: 1.05rem;
font-weight: 700;
color: #1a1a1a;
margin-bottom: 8px;
} 

.benefit-card p {
color: #555;
line-height: 1.65;
margin: 0;
font-size: .95rem;
}

/* CHECKLIST */

.checklist {
    display: flex;
    flex-direction: column;
    gap: 28px;
    margin-top: 30px;
    width: 100%;
}

.check-item {
    display: flex;
    align-items: flex-start;
    gap: 18px;
    width: 100%;
}

.check-icon {
    width: 38px;
    height: 38px;
    min-width: 38px;
    border-radius: 50%;
    background: rgba(255,255,255,.25);
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    font-weight: 700;
    flex-shrink: 0;
}

.check-item > div:last-child {
    flex: 1;
}

.check-title {
    font-size: 1.1rem;
    font-weight: 700;
    margin-bottom: 8px;
    line-height: 1.4;
}

.check-title.white {
    color: #fff;
}

.check-title.dark {
    color: #000;
}

.check-text {
    color: rgba(0,0,0,.85);
    font-size: 0.95rem;
    line-height: 1.8;
    margin: 0;
}

/* CTA */
.cta-content{
flex-grow: 1;
display: flex;
flex-direction: column;
align-items: center;
text-align: center;
padding: 72px 48px;
}

.cta-title {
font-size: clamp(1.6rem, 3vw, 2.4rem);
font-weight: 700;
color: #fff;
margin-bottom: 16px;
}

.cta-text {
color: rgba(255,255,255,.85);
max-width: 500px;
line-height: 1.7;
margin-bottom: 36px;
} 

.cta-btn {
background: rgba(255,255,255,.5);
color: var(--brand);
border: none;
border-radius: 999px;
padding: 14px 40px;
font-weight: 700;
font-size: 1rem;
cursor: pointer;
box-shadow: 0 8px 24px rgba(0,0,0,.15);
} 
.sec-4 .content-column {
    width: 50% !important;
    max-width: 50% !important;
    flex: 0 0 50% !important;
}

.sec-4 .image-column {
    width: 50% !important;
    max-width: 50% !important;
    flex: 0 0 50% !important;
}
