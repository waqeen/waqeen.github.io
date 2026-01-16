---
layout: default
title: Home
---

<div class="space-y-12 animate-fadeIn">
    <div class="text-center space-y-4 py-12">
        
        <div class="flex justify-center mb-6">
            <div class="bg-white p-2 rounded-2xl shadow-lg inline-block">
                <img src="{{ '/assets/images/avatar.png' | relative_url }}" 
                     alt="Avatar" 
                     class="w-32 h-32 rounded-xl object-cover" />
            </div>
        </div>

        <h1 class="text-5xl font-bold bg-clip-text text-transparent bg-[linear-gradient(to_right,rgb(76,29,149),rgb(185,28,28),rgb(109,40,217))]">
            waqeen, SOC Analyst & Threat Hunter & DFIR Expert
        </h1>
        
        <p class="text-xl text-gray-600 max-w-2xl mx-auto">
            Active member of the cybersecurity community and have participated in multiple competitions as both a Blue and Red Team
        </p>
    </div>

    <div class="mt-16 space-y-6">
        <h2 class="text-lg font-bold text-red-600 uppercase tracking-widest text-center">
            My Profile Pages
        </h2>

        <div class="flex flex-wrap justify-center items-center gap-6">
            
            <div class="flex items-center justify-center overflow-hidden w-[300px] h-[100px]">
                <div class="scale-90 transform origin-center">
                    <script src="https://cyberdefenders.org/p/waqeen/badge"></script>
                </div>
            </div>

            <div class="flex items-center justify-center overflow-hidden w-[300px] h-[100px]">
                <iframe 
                    src="https://tryhackme.com/api/v2/badges/public-profile?userPublicId=621364" 
                    style="border:none; width: 300px; height: 90px;" 
                    scrolling="no">
                </iframe>
            </div>

            <a href="https://blueteamlabs.online/public/user/f8570d7881b8424a7acf39" target="_blank" class="transition-transform hover:scale-105">
                <img src="{{ '/assets/images/btlo_badge.png' | relative_url }}" 
                    alt="BTLO Profile" 
                    class="w-[200px] h-auto rounded-lg shadow-sm border border-gray-100">
            </a>

            <a href="https://app.hackthebox.com/public/users/978422" target="_blank" class="transition-transform hover:scale-105">
                <img src="https://www.hackthebox.eu/badge/image/978422" 
                    alt="HTB Profile" 
                    class="h-[80px] w-auto"> 
            </a>

        </div>
    </div>

    <div class="mt-20 grid md:grid-cols-2 gap-8">
    <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm">
        <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
            <span class="text-red-600">🛡️</span> Blue Team Skills
        </h3>
        <div class="flex flex-wrap gap-2">
            {% assign skills = "SOC Operations,Incident Response,Digital Forensics,Threat Hunting,Log Analysis,SIEM" | split: "," %}
            {% for skill in skills %}
                <span class="px-3 py-1 bg-red-50 text-red-700 rounded-full text-xs font-bold">{{ skill }}</span>
            {% endfor %}
        </div>
    </div>

    <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm">
        <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
            <span class="text-red-600">🛠️</span> Tools
        </h3>
        <div class="flex flex-wrap gap-2">
            {% assign tools = "Splunk,Wireshark,Volatility,Autopsy,EricZimmerman Tools,ELK" | split: "," %}
            {% for tool in tools %}
                <span class="px-3 py-1 bg-gray-100 text-gray-700 rounded-full text-xs font-bold">{{ tool }}</span>
            {% endfor %}
        </div>
    </div>
</div>
    
</div>