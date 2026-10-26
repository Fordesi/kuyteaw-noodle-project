# Goal

A landing page for โอ้โฮ! นิว ลูกชิ้นปลานายใบ้ (Nai Bai fish ball noodles) that works as the restaurant's front door **and** makes the franchise offer easy to find and understand.

## What the page must do
1. Show what the restaurant is: brand, menu, branches, how to order.
2. Make the franchise offer easy to find (visible from the top of the page, not buried).
3. Make the franchise offer easy to understand: what you pay, what you get, what the rules are, who to call.
4. Turn interest into a call or message to Khun Por (095-329-6494) in one tap.

## Audience
- Customers: hungry people on a phone, usually coming from Facebook or Lineman.
- Franchise prospects: first-time business owners with no food experience (the pitch is "no experience needed").

## Scope
In:
- One page, mobile first.
- Sections: hero, menu, branches/ordering, franchise (packages, what's included, conditions, FAQ), proof (reviews), contact.
- Franchise: 49,000 and 79,000 baht packages side by side, with the 79k Set A (cart) / Set B (lightbox sign) choice shown clearly.
- Click-to-call, Facebook page link, Lineman links, franchise Reel link.

Out (unless asked later):
- Backend, login, online ordering, payments.
- Application form (use click-to-call and Messenger instead).
- Break-even calculator and "which package fits me" picker (nice to have, needs owner data).

## Content sources
- Facts: `info/naibai-facebook-info.md`
- Images: `pics/` (franchise flyers, food, menu graphics, shop and stall, kitchen, delivery screenshots)
- Franchise details come from the two flyers in `pics/franchise/`; do not invent numbers.

## Done when
- A visitor can find the franchise section within one scroll on a phone.
- Both packages, their contents and the three revocation conditions can be read without opening the flyer images.
- Every call/order button works (`tel:`, Facebook, Lineman).
- Nothing unverified is shown as fact (items marked **?** in the info file stay out or show as "ask us").

## Blocked on the owner (leave as placeholders, do not guess)
- Whether the 79k buyer gets Set A, Set B or both.
- Royalty or extra fees, contract length, territory rules.
- The two unreadable starter-pack items.
- Street address and map pin (postcode 11000 is Nonthaburi, flyers say Samyan).
- Opening hours, confirmed menu prices, founder/brand story.

## Open decisions (defaults assumed until you say otherwise)
- Language: Thai first, English optional. Default: Thai.
- Stack: one static `index.html` plus `pics/`, no build step. Default: static.
