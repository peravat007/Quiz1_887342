# Quiz1_887342
Us_states = {
    "Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}
puts "_________________________________________________________" 
puts "***********************1*********************************"

 Us_states.each {|fullname,mininame|
       if mininame[1]=="T"||mininame[1]=="N"
    puts mininame
 end
}
puts "_________________________________________________________"

 puts Us_states.sort.reverse 
puts "_________________________________________________________"

 Us_states.each {|x,y|
    if (x.downcase[0]=="a"||x.downcase[0]=="e"||x.downcase[0]=="i"||x.downcase[0]=="o"||x.downcase[0]=="u")&&(x.downcase[-1]=="a"||x.downcase[-1]=="e"||x.downcase[-1]=="i"||x.downcase[-1]=="o"||x.downcase[-1]=="u")
        puts x
    end
 }
 puts "_________________________________________________________"
 puts "***********************2*********************************"
require 'prime'
print "Enter your number : "
 k=gets.chomp.to_i

Prime.each(k) do |prime|
  p prime  #=> 2, 3, 5, 7, 11, ...., 97
end
puts "_________________________________________________________"

 เสร็จ1ข้อใหญ่  ข้อ2 ยังไม่สมบูรณ์ครับ
