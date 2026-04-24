---
title: Kontakt
menu: Kontakt
process:
    markdown: true
    twig: true
---

<style>
.contact-card {
    display: flex;
    align-items: center;
    gap: 20px;
    background: #f9f9f9;
    padding: 20px;
    border-left: 5px solid #0056b3;
    text-align: left;
}

.contact-card img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.contact-info h3 {
    margin: 0;
    color: #0056b3;
}

@media screen and (max-width: 639px) {
    .contact-card {
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        border-left: none;
        border-top: 5px solid #0056b3;
    }
    
    .contact-info {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
}
</style>

## Kontakt i Dane Firmy

<div class="contact-card">
    <img src="{{ url('theme://images/michal_kojdecki.jpg') }}" alt="Michał Kojdecki">
    <div class="contact-info">
        <h3>Michał Kojdecki</h3>
        <p style="margin: 5px 0; font-weight: bold;">Prokurent</p>
        <p style="margin: 0;">📞 797-712-972</p>
        <p style="margin: 0;">☎️ 32 307 90 90</p>
        <p style="margin: 0;">📧 biuro@zdi24.pl</p>
        <p style="margin: 15px 0 5px 0; color: #0056b3; font-weight: bold;">Dane teleadresowe</p>
        <p style="margin: 0;">ZDI24.PL Sp. z o.o.</p>
        <p style="margin: 0;">43-100 Tychy, ul. Długa 19</p>
        <p style="margin: 0;">NIP: 646-290-30-76</p>
        <p style="margin: 0;">REGON: 241825700</p>
        <p style="margin: 0;">KRS: 0000376747</p>
    </div>
</div>