import com.scalakata._

@instrument class Playground {
 case class Time( hours : Int = 0 ,minutes : Int = 0)
  
  object Hello{
    
    val oneHourInMinutes : Int = 60
    
    def createTimeFromMinutes(minutes : Int) = 
    new Time( 
      minutes/oneHourInMinutes,
      minutes%oneHourInMinutes
    )
  }
  
  Hello.createTimeFromMinutes(230)
}
