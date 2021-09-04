<div align=center>
    
![Willis](https://user-images.githubusercontent.com/85594230/132092695-e7727276-2782-42dd-a42c-24d927d85088.mp4) 

</div>

## About Me

```TypeScript
import { contact, IUser } from './github'

export default class ME implements IUser {
    public static firstName = 'Lucky'
    public static lastName = 'Yambem'
    public static username = 'ShinNouzen'
    public static aliases = ['Shin']
    public static skills = [
        'TypeScript', 
        'JavaScript', 
        'NodeJS',
        'HTML',
        'CSS',
        'C++'

    ], 
    public static info = {
        age: 15,
        country: 'India',
        org: 'None',
        likes: [
            'Chitoge Kirisaki',
            'JavaScript',                                    
            'NodeJS',
            'TypeScript,
            'HTML',
            'CSS',
            'C++',
            'Anime'
        
        ],
        reach: [
            {
                name: contact.Discord,
                username: 'Shin Nouzen#4457'
            },
            {
                name: contact.WhatsApp,
                url: 'https://wa.me/917005014836?text=Hmm'
            },
            {
                name: contact.Instagram
                username: '_lucky_yam_'
            },
            {
                name: contact.Facebook
                username: 'Lucky Yambem'
            },
            {   name: contact.Twitter
                username: 'Shin Nouzen (@NouzenShin)'
            }
        ]
    }
