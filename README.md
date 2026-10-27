
transition: opacity 0.2s;
}

.phone-btn:hover {
opacity: 0.9;
}

/* Dynamic button fills */
.teal-card .phone-btn { background-color: var(--card-teal); }
.blue-card .phone-btn { background-color: var(--card-blue); }
.yellow-card .phone-btn { background-color: var(--card-yellow); }
.red-card .phone-btn { background-color: var(--card-red); }

.note {
font-size: 11px;
color: #6b7280;
margin-top: 5px;
font-style: italic;
}

/* Footer Section */
.footer {
text-align: center;
padding: 0 25px;
}

.footer h3 {
font-size: 16px;
color: #111827;
margin-bottom: 8px;
}

.footer p {
font-size: 13px;
color: #6b7280;
margin: 5px 0;
}
</style>
</head>
<body>

<div class="schedule-container">

<!-- Top Header Banner -->
<div class="header">
<h1>Consulting</h1>
<h2>Schedule</h2>
<div class="doctor-info">
<span class="doctor-name">DR K P ASHRAF</span>
<span class="doctor-degree">MBBS MD (Pediatrics)</span>
</div>
</div>

<!-- OPD Locations Grid -->
<div class="grid-container">

<!-- Location 1: KIMS Sreechand -->
<div class="card teal-card">
<div class="hospital-name">KIMS Sreechand Hospital, Kannur</div>
<div>
<div class="time-slot">🕒 7:30 AM - 1:30 PM</div>
<a href="tel:04972715550" class="phone-btn">📞 0497 2715550</a>
</div>
</div>

<!-- Location 2: Fathima Hospital -->
<div class="card blue-card">
<div class="hospital-name">Fathima Hospital, Kannur</div>
<div>
<div class="time-slot">🕒 2:30 PM - 4:30 PM</div>
<a href="tel:6262888000" class="phone-btn">📞 62628 88000</a>
</div>
</div>

<!-- Location 3: Medister Specialist Clinics -->
<div class="card yellow-card">
<div class="hospital-name">Medister Specialist Clinics, Varam</div>
<div>
<div class="time-slot">🕒 4:30 PM - 7:30 PM</div>
<a href="tel:8281292177" class="phone-btn">📞 82812 92177</a>
<div class="note">(booking starts after 10:30 am)</div>
</div>
</div>

<!-- Location 4: Crescent Hospital -->
<div class="card red-card">
<div class="hospital-name">Crescent Hospital, Thana, Kannur</div>
<div>
<div class="time-slot">🕒 7:30 PM - 8:30 PM</div>
<a href="tel:7970608759" class="phone-btn">📞 79706 08759</a>
</div>
</div>

</div>

<!-- Booking Disclaimers and Info -->
<div class="footer">
<h3>For Bookings & Appointments:</h3>
<p>Please Contact the respective Hospitals/Clinics by clicking the phone numbers above.</p>
<p style="font-weight: 600; color: #0284c7; margin-top: 15px;">Available for consultations at four prime locations in Kannur.</p>
</div>

</div>

</body>
</html>
