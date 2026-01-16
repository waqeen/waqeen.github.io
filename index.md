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
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-20">
        <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
            <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                <span class="text-green-600">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                </span> About Me
            </h3>
            <div class="flex flex-wrap gap-2">
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">23 y.o</span>
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">🇷🇺 Russian (Native)</span>
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">🇬🇧 English (C1)</span>
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">🇮🇹 Italian (A2)</span>
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">GSOC</span>
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">Book reader</span>
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">Basketball</span>
                <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-[11px] font-bold">Cybersecurity competitions enjoyer</span>
            </div>
        </div>
        <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
            <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                <span class="text-blue-600">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path></svg>
                </span> Blue Team Skills
            </h3>
            <div class="flex flex-wrap gap-2">
                {% assign blue_skills = "SOC Operations,Incident Response,Digital Forensics,Threat Hunting,Log Analysis,SIEM" | split: "," %}
                {% for skill in blue_skills %}
                    <span class="px-3 py-1 bg-blue-50 text-blue-700 rounded-full text-[11px] font-bold">{{ skill }}</span>
                {% endfor %}
            </div>
        </div>
        <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
            <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                <span class="text-red-600">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 9.5 15 10"/><path d="m10 14.5-.5.5"/><path d="m10 9.5 4.5 5.5"/><path d="m14.5 14.5-4.5-4.5"/><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><path d="m4.5 16.5 3-3"/><path d="m16.5 4.5-3 3"/></svg>
                </span> Red Team Skills
            </h3>
            <div class="flex flex-wrap gap-2">
                {% assign red_skills = "OWASP Top-10,Active Directory,Linux,Windows,Smart Contract attacks" | split: "," %}
                {% for skill in red_skills %}
                    <span class="px-3 py-1 bg-red-50 text-red-700 rounded-full text-[11px] font-bold">{{ skill }}</span>
                {% endfor %}
            </div>
        </div>
        <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
            <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                <span class="text-yellow-500">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m7.5 4.27 9 5.15"/><path d="M21 8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16Z"/><path d="m3.3 7 8.7 5 8.7-5"/><path d="M12 22V12"/></svg>
                </span> Related Skills
            </h3>
            <div class="flex flex-wrap gap-2">
                {% assign related = "MlSecOps,Blockchain,Report writing,UEBA,Article writing" | split: "," %}
                {% for skill in related %}
                    <span class="px-3 py-1 bg-yellow-50 text-yellow-700 rounded-full text-[11px] font-bold">{{ skill }}</span>
                {% endfor %}
            </div>
        </div>
    </div>
    <div class="mt-12 space-y-8">
        <h2 class="text-lg font-bold text-red-600 uppercase tracking-widest text-center">
            My Profile Pages
        </h2>

        <div class="flex flex-wrap justify-center items-center gap-10">
            
            <div class="min-w-[300px] flex justify-center">
                <div class="scale-90 transform">
                    <script src="https://cyberdefenders.org/p/waqeen/badge"></script>
                </div>
            </div>

            <div class="min-w-[300px] flex justify-center">
                <iframe 
                    src="https://tryhackme.com/api/v2/badges/public-profile?userPublicId=621364" 
                    style="border:none; width: 300px; height: 90px;" 
                    scrolling="no">
                </iframe>
            </div>

            <a href="https://blueteamlabs.online/home/user/f8570d7881b8424a7acf39" target="_blank" class="hover:opacity-80 transition-opacity">
                <img src="{{ '/assets/images/btlo_badge.png' | relative_url }}" 
                    alt="BTLO Profile" 
                    class="h-[80px] w-auto">
            </a>

            <a href="https://app.hackthebox.com/users/978422" target="_blank" class="hover:opacity-80 transition-opacity">
                <img src="https://www.hackthebox.eu/badge/image/978422" 
                    alt="HTB Profile" 
                    class="h-[80px] w-auto">
            </a>
        </div>
    </div>        
    
    
</div>