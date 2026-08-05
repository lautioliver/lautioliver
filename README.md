```typescript
module main

main :: func(): void {
    lautaro :: aboutMe = {
        name: ["Lautaro Zahir Oliver"],
        knownAs: ["Lauti"],
        pronouns: ["He", "Him"],
        role: ["Computer Engineering Student @ UCASAL"],
        location: ["Salta, Argentina 🇦🇷"],
        stack: ["TypeScript", "Next.js", "React", "Tailwind CSS", "PostgreSQL", "Python"],
        currentProjects: ["UcaNode"],
        hobbies: ["Coding", "Chess", "F1"],
        funFact: ["I build local scripts to automate my university workflow."]
    };

    println "Name: ${lautaro.name}";
    println "Role: ${lautaro.role}";
    println "Location: ${lautaro.location}";
    println "Stack: ${lautaro.stack}";
    println "Building: ${lautaro.currentProjects}";
    println "Hobbies: ${lautaro.hobbies}";
    println "Fun Fact: ${lautaro.funFact}";
}
