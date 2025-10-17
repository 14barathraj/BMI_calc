BMI Calculator — Short Project Overview
A BMI (Body Mass Index) calculator is a small, user-friendly web tool built with HTML, CSS, and JavaScript that helps users estimate
whether their weight is in a healthy range for their height. The app takes height and weight (in metric or imperial units), 
computes BMI using the formula BMI = weight (kg) / (height (m))², and shows the result along with a short interpretation (underweight, normal, overweight, obese). 
Visually it usually has a simple input form, clear result card, subtle animations for feedback, and validation to prevent wrong inputs. 
This project is great for learning DOM manipulation, form handling, unit conversion, and designing accessible, responsive UI.

Quick side topics (useful details & enhancements)

Formula & Units

Metric: BMI = kg / (m * m). If height is given in cm, convert: m = cm / 100.

Imperial: BMI = (lbs / (in * in)) * 703.

BMI Categories (WHO common ranges)

Underweight: BMI < 18.5

Normal weight: 18.5 – 24.9

Overweight: 25.0 – 29.9

Obesity (Class I): 30.0 – 34.9

Obesity (Class II): 35.0 – 39.9

Obesity (Class III): ≥ 40.0

Front-end features to include

Inputs for weight and height + unit selector (kg/cm or lbs/in).

Immediate validation (non-empty, positive numbers) and friendly error messages.

Live result card showing BMI (rounded to one decimal) and the category with a color cue.

Responsive layout so it works on phones and desktops.

Optionally animate the result number counting up for a nice effect.

Accessibility & UX

Use semantic HTML (<form>, <label>, <input>, <output>).

Ensure keyboard focus order and ARIA labels for screen readers.

High-contrast color choices for readability.

Advanced enhancements

Save past calculations to localStorage and show history.

Add guidance or recommended BMI ranges by age/sex if needed (with disclaimers).

Integrate a printable summary or shareable link.

Add charting (weight vs. time) if tracking over days/weeks.

Health & legal note

BMI is a simple population-level indicator and doesn’t account for muscle mass, bone density, or body composition. Include a short disclaimer: “This tool provides an estimate only — consult a healthcare professional for personalized advice
