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
<table>
<tr>
<td>
<img align="center" src="https://github-readme-stats.vercel.app/api?username=gvanastasov&theme=darcula&count_private=true&show_icons=true&include_all_commits=true&rank_icon=github&bg_color=transparent" width="441" />
</td>
<td>
<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gvanastasov&size_weight=0.5&count_weight=0.5&langs_count=8&layout=donut&theme=darcula&bg_color=transparent" width="441" />
</td>
</tr>
</table>
