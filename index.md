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

        <div class="mt-16 space-y-8">
            <h2 class="text-lg font-bold text-red-600 uppercase tracking-widest text-center">
                My Profile Pages
            </h2>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 items-stretch">
                
                <div class="flex items-center justify-center p-4 bg-[#1a1f2b] rounded-xl border border-gray-100 shadow-sm hover:shadow-md transition-all">
                    <div class="scale-[0.85] origin-center">
                        <script src="https://cyberdefenders.org/p/waqeen/badge"></script>
                    </div>
                </div>

                <div class="flex items-center justify-center p-4 bg-[#1a1f2b] rounded-xl border border-gray-100 shadow-sm hover:shadow-md transition-all">
                    <iframe 
                        src="https://tryhackme.com/api/v2/badges/public-profile?userPublicId=621364" 
                        style="border:none; width: 300px; height: 90px;" 
                        class="scale-90"
                        scrolling="no">
                    </iframe>
                </div>

                <a href="https://blueteamlabs.online/home/public-profile/ТВОЙ_ID" target="_blank" 
                class="flex items-center justify-center p-4 bg-[#0d1117] rounded-xl border border-gray-100 shadow-sm hover:shadow-md transition-all group">
                    <img src="{{ '/assets/images/btlo_badge.png' | relative_url }}" 
                        alt="BTLO" 
                        class="max-w-full h-auto group-hover:scale-105 transition-transform">
                </a>

                <a href="https://app.hackthebox.com/users/960" target="_blank" 
                class="flex items-center justify-center p-4 bg-[#141d2b] rounded-xl border border-gray-100 shadow-sm hover:shadow-md transition-all group">
                    <img src="https://www.hackthebox.eu/badge/image/960" 
                        alt="HTB" 
                        class="max-w-full h-auto group-hover:scale-105 transition-transform">
                </a>

            </div>
        </div>

        <div class="mt-20 grid grid-cols-1 md:grid-cols-2 gap-6">
            
            <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
                <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                    <span class="text-green-600">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                    </span> 
                    About Me
                </h3>
                <div class="flex flex-wrap gap-2">
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">23 y.o</span>
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">🇷🇺 Russian (Native)</span>
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">🇬🇧 English (C1)</span>
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">🇮🇹 Italian (A2)</span>
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">GSOC</span>
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">Book reader</span>
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">Basketball</span>
                    <span class="px-3 py-1 bg-green-50 text-green-700 rounded-full text-xs font-bold">Cybersecurity competitions enjoyer</span>
                </div>
            </div>

            <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
                <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                    <span class="text-blue-600">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path></svg>
                    </span>
                    Blue Team Skills
                </h3>
                <div class="flex flex-wrap gap-2">
                    {% assign blue_skills = "SOC Operations,Incident Response,Digital Forensics,Threat Hunting,Log Analysis,SIEM" | split: "," %}
                    {% for skill in blue_skills %}
                        <span class="px-3 py-1 bg-blue-50 text-blue-700 rounded-full text-xs font-bold">{{ skill }}</span>
                    {% endfor %}
                </div>
            </div>

            <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
                <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                    <span class="text-red-600">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="14.5" y1="9.5" x2="15" y2="10"></line><line x1="10" y1="14.5" x2="9.5" y2="15"></line><line x1="10" y1="9.5" x2="14.5" y2="15"></line><line x1="14.5" y1="14.5" x2="10" y2="10"></line><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path><line x1="4.5" y1="16.5" x2="7.5" y2="13.5"></line><line x1="16.5" y1="4.5" x2="13.5" y2="7.5"></line></svg>
                    </span>
                    Red Team Skills
                </h3>
                <div class="flex flex-wrap gap-2">
                    {% assign red_skills = "OWASP Top-10,Active Directory,Linux,Windows,Smart Contract attacks" | split: "," %}
                    {% for skill in red_skills %}
                        <span class="px-3 py-1 bg-red-50 text-red-700 rounded-full text-xs font-bold">{{ skill }}</span>
                    {% endfor %}
                </div>
            </div>

            <div class="p-6 bg-white rounded-2xl border border-gray-100 shadow-sm flex flex-col">
                <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                    <span class="text-yellow-500">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"></path><polyline points="3.27 6.96 12 12.01 20.73 6.96"></polyline><line x1="12" y1="22.08" x2="12" y2="12"></line></svg>
                    </span>
                    Related Skills
                </h3>
                <div class="flex flex-wrap gap-2">
                    {% assign related = "MlSecOps,Blockchain,Report writing,UEBA,Article writing" | split: "," %}
                    {% for skill in related %}
                        <span class="px-3 py-1 bg-yellow-50 text-yellow-700 rounded-full text-xs font-bold">{{ skill }}</span>
                    {% endfor %}
                </div>
            </div>

        </div>
</div>
    
</div>