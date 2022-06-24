# do-while-loop-of-array

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ARAYKO
{
    internal class Program
    {
        

        static void Main(string[] args)
        {
            int adobo = 60;
            int dinuguan = 50;
            int bulalo = 40;
            int porkchop = 70;
            int gulay = 30;


            {

                Console.WriteLine("Do you want know the price... \nPress Y to yes... \nPress any key to no...");
                string select = Console.ReadLine();
                if (select == "Y")
                {

                    do
                    {




                        int[] arr = { adobo, dinuguan, bulalo, porkchop, gulay };
                        Console.WriteLine("The price is:");
                        foreach (int i in arr)
                            Console.WriteLine(i);
                        Console.WriteLine("Do you want to try again... \nPress Y to yes... \nPress any key to no...");


                    } while (Console.ReadLine().ToUpper() == "Y");
                }


                else
                {
                    Console.ReadKey();
                }
                
                }

            }
        }
    }



