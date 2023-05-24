![visitors](https://visitor-badge.glitch.me/badge?page_id=gvanastasov.visitor-badge&left_color=green&right_color=red)
```cs
using Github;

namespace gvanastasov 
{
    [Description("Awesome")]
    public sealed class Me : Architect, 
    	ILeader, IDeveloper, IProgrammer, INinja
    {
        public dynamic Occupation => new
        {
            Company: "Telia Company",
            Position: "Domain Architect",
        };
        
        public string Level => "expert";
        public string Passion => "coding";
	public string Hacks => "fruit";
        
        public DateTime CodingSince => DateTime.Now.AddYears(-19);
        public CoffeeType CoffeeType => CoffeeType.Any;
        
        public List<Type> Knowledge = new List<Type>
        {
	    typeof(CSharp),
	    typeof(Node),
            typeof(Javascript),
            typeof(Vuejs),
            typeof(React),
	    typeof(Flutter),
	    typeof(AWS),
	    typeof(CMS),
	    typeof(GraphQL),
	    // todo: use {{ System.Reflection }} to get all of them...
        };
        
        public string GetGoals(string @for)
        {
            switch(@for)
                case "personal": 
		    return "Relax and enjoy life.";
                case "work": 
		    return "Do awesome stuff and drink coffee with team.";
		case "before 8am":
		    return "Get me some coffee...";
                default: 
		    return "Just be happy and code.";
        }
    }
}
```

<!--
**gvanastasov/gvanastasov** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
