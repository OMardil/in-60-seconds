public class RoomOccupancy {

    private int floorNumber;
    private int roomNumber;
    private int peopleInRoom;
    
    public RoomOccupancy(int floorNumber, int roomNumber) {
        this.floorNumber = floorNumber;
        this.setRoomNumber(roomNumber);
        this.peopleInRoom = 0;
    }
        

    public int getFloorNumber() {
        return floorNumber;
    }

    public int getRoomNumber() {
        return roomNumber;
    }

    public int getPeopleInRoom() {
        return peopleInRoom;
    }

    public void setRoomNumber(int roomNumber) {
        if (roomNumber > 0 ) 
            this.roomNumber = roomNumber;
    }
    
    public void addOneToRoom(){
        this.peopleInRoom += 1;
    }


    
}