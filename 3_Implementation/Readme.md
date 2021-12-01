
#include <avr/io.h>
#include <util/delay.h>


int main(void)
{
    // initialize digital pins 0-7 as outputs
    DDRD = 0xFF; //0b11111111

    // infinite loop
    while(1){

    PORTD = 0x3F;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x06;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x5B;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x4F;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x66;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x6D;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x7D;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x07;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x7F;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);

    PORTD = 0x6F;
    _delay_ms(1000);
    PORTD = 0x00;
    _delay_ms(1000);
    }
}


