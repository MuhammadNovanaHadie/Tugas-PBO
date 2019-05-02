# Tugas-PBO
Tugas PBO
package mdl5;


public class trigonomtr {
    float sin;
    float cos;
    float tan;
    
    public float getSin(){
        return (float) Math.sin(Math.toRadians(sin));
    }
    public void setSin(float sin){
        this.sin = sin;
    }
    public float getCos(){
        return (float) Math.cos(Math.toRadians(cos));
    }
    public void setCos(float cos){
        this.cos = cos;
    }
    public float getTan(){
        return (float) Math.tan(Math.toRadians(tan));
    }
    public void setTan(float tan){
        this.tan = tan;
    }
    
}
