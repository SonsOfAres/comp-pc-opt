+++
template = "landing.html"
title = "Competitive PC Optimization"

[extra]
version = "v0.0.1"

# Section order configuration - customize the order of landing page sections
# Available sections: "hero", "features", "trust", "easy_command", "showcase", "social_proof", "final_cta"
# If not specified, default order is used: hero -> features -> trust -> easy_command -> showcase -> social_proof -> final_cta
section_order = ["hero", "features", "trust", "easy_command", "showcase", "social_proof", "final_cta"]

[extra.hero]
title = "Competitive PC Optimization"
badge = "From Silicon to the Pip"
description = "Compiled from many pilots, operators, and one galactic-conquest obsessed AI who absolutely refuses to let friends play at 30 FPS."
image = "/images/ARES-on-stone-texture-1080.png"
gradient_opacity = 70
image_opacity = 30
cta_buttons = [
    { text = "Download Guide", url = "/introduction", style = "primary" },
]

[extra.features_section]
title = "Essential Features"
description = "Reduce latency, stabilize frames, and hit more shots."

[[extra.features_section.features]]
title = "Targeting Consistency"
desc = "Better 1% lows and cleaner frame pacing mean your pip behaves predictably, your aim feels stable, and tracking stays reliable instead of fighting micro-stutter."
icon = "fa-solid fa-crosshairs"

[[extra.features_section.features]]
title = "Frame Pacing Over Max FPS"
desc = "We break down settings and hardware choices that smooth spikes and keep motion readable under stress. Consistent frame timing wins fights."
icon = "fa-solid fa-film"

[[extra.features_section.features]]
title = "Competitive Reality"
desc = "Optimized for high-speed PvP, large fights, and precision flying — where cache, latency, and visibility matter more than synthetic benchmarks 🚀"
icon = "fa-solid fa-jet-fighter-up"

[extra.trust_section]
title = "Tech Stack"
logos = [
    { src = "/resources/Windows-icon-vector-13.svg", alt = "Windows" },
    { src = "/resources/Nvidia-Geforce-GTX-logo-vector-01.svg", alt = "Nvidia GeForce GTX" },
    { src = "/resources/AMD-logo-vector-01.svg", alt = "AMD" },
    { src = "/resources/AMD-Radeon-Graphics-logo-vector-01.svg", alt = "AMD Radeon" },
    { src = "/resources/Intel-icon-vector-01.svg", alt = "Intel" },
    { src = "/resources/Vulkan_API_logo.svg", alt = "Vulkan" },
]

#[extra.social_proof_section]
#title = "What Our Users Say"
#testimonials = [
#    { author = "KSG", role = "Security Developer / OWASP Noir", quote = "Without extra tools, it includes practical features like search, multilingual support, and comments out of the box", avatar = "/resources/ksg.jpg" },
#    { author = "Lina", role = "Security Engineer", quote = "It's so simple and fast, yet I can apply an incredibly beautiful theme, which I absolutely love! I'm ready to embark on a journey to find the calm in my heart with this theme!", avatar = "/resources/lina.jpg" },
#    { author = "Yertz", role = "Griefer", quote = "Hey! I wrote some of this.", avatar = "/resources/yertz-pfp.png" },
#]

[extra.final_cta_section]
title = "Fly with us"
description = """
Whether you want structured training or just time in the cockpit with people who care about getting better, you’re welcome on the line 🚀✈️
Hop in, ask questions, and train the way competitive Star Citizen is actually played.
"""
button = { text = "Ares Discord", url = "discord.gg/join-ares" }
+++