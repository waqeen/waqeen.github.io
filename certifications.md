---
layout: default
title: Certifications
permalink: /certifications/
---

<div class="space-y-8">
    <div class="text-center space-y-4">
        <h1 class="text-4xl font-bold text-gray-800 flex items-center justify-center gap-3">
            Professional Certifications
        </h1>
        <p class="text-gray-600">Validated expertise in both Red & Blue Teaming</p>
    </div>

    <div class="grid md:grid-cols-2 gap-6">
        {% for cert in site.data.certifications %}
        <div class="bg-white rounded-lg p-6 shadow-lg border-2 border-gray-100 hover:border-blue-300 hover:shadow-xl transition-all group">
            <div class="flex gap-4">
                <div class="flex-shrink-0">
                    <a href="{{ cert.url }}" target="_blank" rel="noopener noreferrer" class="block">
                        <img src="{{ cert.badge }}" alt="{{ cert.name }}" class="w-24 h-24 object-contain rounded-lg group-hover:scale-105 transition-transform">
                    </a>
                </div>
                
                <div class="flex-1 min-w-0">
                    <div class="flex items-start justify-between mb-2">
                        <a href="{{ cert.url }}" target="_blank" rel="noopener noreferrer" class="flex-1 hover:text-blue-600 transition-colors">
                            <h3 class="text-lg font-bold text-gray-800 mb-1 leading-tight">{{ cert.name }}</h3>
                        </a>
                        <span class="px-2 py-1 bg-green-100 text-green-700 rounded-full text-xs font-medium ml-2">
                            {{ cert.status }}
                        </span>
                    </div>
                    <p class="text-gray-600 font-medium mb-2">{{ cert.issuer }}</p>
                    <div class="flex items-center justify-between">
                        <span class="text-gray-500 text-sm">Obtained: {{ cert.year }}</span>
                        <a href="{{ cert.url }}" target="_blank" class="text-blue-600 hover:text-blue-700 text-sm font-medium">Verify →</a>
                    </div>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>
</div>